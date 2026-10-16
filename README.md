# Bunny Munch V10.7 — Carrot Quest 🐰🥕

A single-file offline game. For GitHub Pages, put `index.html` at the root of your repository, commit, and use GitHub Pages (branch main, folder /root).

## New Carrot Quest rules

- Maze 1: Collect 35% of the carrots
- Maze 2: Collect 50% of the carrots
- Maze 3: Collect 65% of the carrots
- Maze 4: Collect 80% of the carrots
- Maze 5: Collect 90% of the carrots
- Maze 6: Collect every carrot (100%)

Goals are rounded **up** to a whole carrot based on how many carrot collectibles actually appear in the generated maze. Candy, stars, shield, and lightning are optional bonus items. The next level starts after reaching the carrot goal.

All five themes are freely selectable. There is no shop or currency. V10.6 artwork and no-bow gameplay are preserved. Records are stored using the same localStorage save key as V10.6.

For offline play, open the standalone HTML file directly in a modern browser. Existing GitHub Pages deployments should replace the old `index.html` with this version.
