# One More Inch — Winding Worlds (V4)

Mobile-first 3D browser game with curved, elevated courses, finger-drag steering, obstacles, and a final Bank or Push challenge.

## Controls
- Touch and hold the 3D game area to accelerate.
- While holding, slide left or right to steer. Steering is relative to the point where you first touched.
- Release to brake. Hold again to accelerate.
- Near the end, stop within the final 12 world units to trigger Bank or Push.
- On Mac: Space to accelerate, arrow keys or A/D to steer.

## Publish
Upload `index.html` to the root of your existing GitHub repository, replacing the older file. GitHub Pages should deploy from `main` / `(root)`.

## Run locally
`python3 -m http.server 8000` then open `http://localhost:8000`.

## Cost
Free static hosting and free Three.js CDN (internet required). No server or paid assets.

## Note
The game has not been device-tested on your particular iPhone. Physics and steering are arcade approximations. Future iterations should refine lateral control and camera based on player feedback.
