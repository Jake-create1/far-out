# Far Out

A psychedelic, retro landing page with a live Three.js scene: a synthwave grid, a striped sun, a morphing iridescent blob and a starfield, with three switchable colour palettes (Sunset, Acid, Cosmic).

Live at https://jake-create1.github.io/far-out/ once GitHub Pages is enabled (Settings → Pages → Deploy from a branch → `main` / root).

## Files

- `index.html` — the whole page (HTML, CSS and the scene script)
- `three.min.js` — Three.js r128 (MIT licence), loaded locally by the page

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```

## To do

- Replace the `[YEAR]` and `[YOUR NAME]` placeholders.
- The email sign-up is a mock: it validates the address and shows a message but sends nothing.
