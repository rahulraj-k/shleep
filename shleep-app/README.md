# Shleep
A responsive, local-first sleep companion built with plain HTML, CSS and JavaScript. No package installation or API key is required to run the prototype.

## Run locally
- Easiest: open `index.html` in a modern browser.
- Recommended local server: from this folder run `npx serve .` (requires Node.js and the `serve` package via npx).

## Deploy to Vercel
1. Create a GitHub repository and upload the contents of this folder.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: **Other**. Build command: leave empty. Output directory: `.`.
4. Deploy. The included `vercel.json` supports clean URLs.

## Current scope
This is a functional local-first MVP. Sleep entries, profile, preferences, habits, weekly commitments and wind-down checklist are saved in the browser's localStorage. Data does not sync between devices and there is no account/authentication or cloud database yet. The sleep timer only runs while the page remains open and is not a dependable alarm. The app intentionally shows no fabricated sleep data.

## Brand assets
Original supplied Shleep logo, theme reference, One-Two-Sleep image and user-journey reference are preserved in `assets/`. The One-Two-Sleep image is shown during the boot transition without any additional caption underneath it.

## Palette
- Deep Indigo: `#0B1F4B`
- Dusk Blue: `#0B1DB8`
- Moonlight Cream: `#FFF3D6`

The app uses Google Fonts when online and falls back to system fonts when offline.
