# Aware Biscuits

Static recreation of the published Framer site [aware-biscuits-630514.framer.app](https://aware-biscuits-630514.framer.app/).

The live Framer page is a single route titled **My Framer Site** (published 2026-09-21). It has no headings or body copy beyond the Framer badge. The page is a full-viewport Three.js canvas of biscuit photographs falling on a white background, with grab-to-orbit interaction.

This repository is **not** the editable Framer project. Framer does not expose project source from a published `.framer.app` URL. What is here is a self-contained HTML/Three.js stand-in that uses the same public biscuit images the published site loads from `framerusercontent.com`.

## Run locally

Open `index.html` in a browser, or:

```bash
npx serve .
```

## GitHub Pages

Settings → Pages → Deploy from branch `main` / root. The site is a single `index.html`.

## Source images

Textures are loaded from the published site's Framer CDN URLs. They remain Framer-hosted assets.
