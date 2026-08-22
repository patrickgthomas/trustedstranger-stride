# Gide Stride

Landing page for Gide Stride, served at `stride.gidehub.com` via GitHub Pages.

`index.html`, `assets/css/app.css` and `assets/js/nav.js` are **generated**. Do not
edit them here. Edit the content in `src/data/apps/stride.json` (and the palette in
`src/data/palettes.json`) in the main Gide site repo, then run:

    node tools/build-app-sites.mjs

Full-size screenshots live in this repo's root; the web-sized WebP copies in
`assets/shots/` are produced by `tools/resize-app-shots.py` in the same repo.
