# Field Notes — Retro Navigation Prototype

A React + Vite prototype for a retro-inspired, nested full-screen navigation menu.

## Features
- Hamburger button opens a full-screen navigation overlay.
- Top-level cassette-inspired cards appear with a staggered entrance.
- Hover and tap feedback on cards.
- Selecting a category reveals second-level cards.
- Back navigation returns to the category list.
- Selecting a second-level item opens a placeholder destination panel.
- Escape key can be added easily; the close button is already included.

## Run locally

Requires Node.js 18+.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Build for production

```bash
npm run build
npm run preview
```

## Customise
Edit the `navigation` array near the top of `src/main.jsx` to change category names, descriptions, labels and submenu items.

Change the visual theme in `src/styles.css`. The illustrated landscape is an original CSS/SVG composition in the `Landscape` component; no external image asset is required.

This is an original prototype inspired by a retro navigation concept, not a copy of Pragyan's source code or assets.
