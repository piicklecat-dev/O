# Jungle Rush VR

A small original browser-based 3D jungle game prototype built with Three.js and WebXR. Intended for desktop browser testing and Meta Quest Browser on Quest 2 / 3 / 3S.

## Play online
After GitHub Pages deployment finishes, visit:
https://piicklecat-dev.github.io/O/

## Controls
- Desktop: WASD/arrow keys to move, mouse drag to look, Space to jump.
- Quest VR: press Enter VR in Meta Quest Browser. Use the left thumbstick to move and right thumbstick to snap-turn. Walk close to the pink spirit to tag it. Find all 10 mangoes.
- Single-player only; there is no online multiplayer or APK yet.

## Hosting
This repository contains a GitHub Actions workflow that publishes the root folder to GitHub Pages. In GitHub, open Actions and look for "Deploy Jungle Rush VR". The first deployment may take a minute or two. If the workflow is blocked, open Settings -> Pages and choose GitHub Actions as the build and deployment source, then re-run the workflow.

## Notes
The site uses the Three.js browser module from jsDelivr. It needs internet access. WebXR requires a secure HTTPS origin and a browser/headset that supports immersive-vr. The experience has not been verified on a physical headset, so compatibility may require fixes after testing.
