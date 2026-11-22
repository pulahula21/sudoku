# Sudoku

A single-page sudoku game with six modes: Classic, Mahjong, Cat Cafe, Dungeon, Reverse and Melody.
Everything (fonts, artwork, sounds) is built into `index.html`. `manifest.webmanifest`, `sw.js`
and `icons/` make it installable and playable offline.

## Publish on GitHub Pages

1. Create a new public repository (for example `sudoku`).
2. Upload every file in this folder, keeping the `icons` folder, to the repository's main branch.
3. In the repository, open Settings > Pages. Under "Build and deployment" choose
   "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute or two the game is live at `https://<your-username>.github.io/sudoku/`.

## Install on a phone

- Android (Chrome): open the link, then menu > Add to Home screen (or Install app).
- iPhone (Safari): open the link, then Share > Add to Home Screen.

Open it once while online so it can cache itself. After that it works in airplane mode.

## Updating

Replace `index.html` in the repository with the new version. Installed copies pick it up
in the background the next time they are opened online, and show it on the launch after that.
