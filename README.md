# WealthWithSG — Animated Subscribe Overlay

A standalone, transparent-background HTML animation for OBS Browser Source. It cycles through **Like the Stream → Subscribe → Turn on the Bell**, then fades away.

## OBS setup

1. In OBS, add a new **Browser** source named `SG Subscribe`.
2. Once the repository is hosted, set the URL to the deployed site's root URL (for example, `https://YOUR-DEPLOYMENT-URL/`).
3. Set width and height to **280 × 280**.
4. Keep **Shutdown source when not visible** enabled so the animation restarts when you show the source again.
5. Position it over a clear corner of the scene, without covering price action or important chart labels.

The page background is transparent. No external libraries, fonts, or image assets are required.

## Timing

The overlay enters, shows three calls to action, and fades out after roughly 9 seconds. To replay it, hide and show the Browser Source (with shutdown-on-hide enabled), or refresh the source.

## Hosting

This is a static site. You can deploy the repository on Vercel by importing `sankalpvoid/SG-subscribe` and using the default settings. The animation will be available at the project's root URL.

