# One More Inch — Risk or Bank (Version 3)

A mobile-first 3D browser arcade game. Free to host on GitHub Pages.

## Improvements
- Hold **anywhere on the 3D game canvas** to accelerate. Release to brake. This avoids iPhone long-press text selection/copy menus.
- Bank or Push after the ball stops; Push gives a risky burst with no brakes.
- Six visually distinct courses (Skyline, Frostbite, Lava Ridge, Golden Dunes, Neon Night, Cloud Nine), each with different handling and scenery.
- Responsive portrait layout, improved lighting, colorful rails, lane markers, score sharing, daily mode, and local best scores.

## Deploy on GitHub Pages
1. Open your GitHub repository `Sanger82/One-more-inch`.
2. Choose **Add file → Upload files** and upload **index.html** from this folder, replacing the existing index.html. Commit changes.
3. Ensure **Settings → Pages → Deploy from a branch → main → /(root)** is selected.
4. Wait for the deployment to finish and open `https://sanger82.github.io/One-more-inch/`.
5. On iPhone Safari, refresh the page if you still see the old game.

## Local testing on Mac
From this folder, run `python3 -m http.server 8000` then open http://localhost:8000.

## Notes
The game loads Three.js 0.160.1 from jsDelivr; an internet connection is needed. No paid services or assets. Level geometry is stylized, and the ball follows a straight gameplay axis even when side details give the course a zigzag appearance. Daily mode is a shared calendar-day course, not an online leaderboard.
