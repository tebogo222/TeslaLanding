<p align="center">
	<img src="images/teslaLogo.png" alt="Project preview" width="220" />
</p>

<p align="center">
	<a href="https://github.com/tebogo222/TeslaLanding"><img src="https://img.shields.io/badge/Repo-TeslaLanding-blue.svg" alt="repo"></a>
	<img src="https://img.shields.io/badge/License-MIT-green.svg" alt="license">
	<img src="https://img.shields.io/badge/Status-Prototype-orange.svg" alt="status">
</p>

# Tesla Landing

A sleek, responsive landing page inspired by Tesla — built with plain HTML, CSS, and JavaScript. Clean, accessible, and easy to customize for your product.

## Table of contents
- [Quick demo](#quick-demo)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Quick start](#quick-start)
- [Project structure](#project-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License & credits](#license--credits)

## Quick demo

Open `index.html` in your browser to preview locally, or serve the folder to test features that require a server.

```powershell
Start-Process .\index.html
```

Preview (centered for clarity):

<p align="center">
	<img src="images/teslaLogo.png" alt="Preview screenshot" width="600" />
</p>

## Features

- ✅ Responsive layout (mobile → desktop)
- ✅ Minimal dependencies — no build step
- ✅ Semantic, accessible markup
- ✅ Simple animations and lightweight JS

## Tech stack

- HTML5 — `index.html`
- CSS3 — `index.css` (variables for quick theming)
- JavaScript — `script.js` (small, unobtrusive behavior)

## Quick start

No build tools required.

```powershell
# Open directly (Windows PowerShell)
Start-Process .\index.html

# Serve with Python (recommended for full testing)
python -m http.server 8000; Start-Process http://localhost:8000

# Or use a node static server if you prefer
npx serve .
```

Then open `http://localhost:8000` (or the URL printed by your server).

## Project structure

- `index.html` — main markup and content
- `index.css` — styles, layout, and variables
- `script.js` — interactivity and small UI tweaks
- `images/` — visual assets (logo, hero, screenshots)
- `README.md` — this file

## Customization

- Replace images in `images/` to change the hero or logo.
- Edit color variables at the top of `index.css` to adapt the palette.
- Update copy directly in `index.html` to reflect your product messaging.

Tips:
- Optimize hero images (WebP or compressed JPG) for faster load times.
- Keep CTA copy short and action-oriented.

## Deployment

Recommended quick options:

- **GitHub Pages** — push the repo and enable Pages from `main`.
- **Netlify / Vercel** — drag-and-drop the folder or connect your repo for CI deploys.

## Contributing

Small fixes and documentation improvements are welcome — open a PR. For major changes, open an issue first to discuss scope.

## License & credits

- License: MIT
- Designed with inspiration from Tesla product pages; implemented by the repository owner.

---

If you'd like, I can also:
- Add a `LICENSE` file with the MIT text.
- Generate and add a `images/screenshot.png` preview image.
- Add a `package.json` with a `start` script that runs a local static server.

Tell me which you'd like next and I'll add it.
