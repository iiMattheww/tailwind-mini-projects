
# Tailwind Mini Projects

A collection of small, focused UI examples built with Tailwind CSS. These mini-projects are intended for practice, reference, and quick reuse of useful Tailwind patterns.

Each folder contains a single standalone example with a ready-to-open `index.html` and an `images/` folder for assets.

Included projects

- `Email-Subscribe-Card/` — email subscribe card component
- `Image-Gallery/` — responsive image gallery with hover overlays
- `Login-Modal/` — login modal UI (example)
- `Pricing-Cards/` — responsive pricing cards grid
- `Product-Modal/` — product detail modal

Quick start

1. Open any mini-project's `index.html` in your browser (double-click in Explorer or use the `ii` alias in PowerShell):

	ii .\Email-Subscribe-Card\index.html

2. Or serve the folder with a simple HTTP server (recommended when loading assets):

	# requires Python 3
	python -m http.server 8000

	Then open http://localhost:8000/ in your browser and navigate to a project folder.

Notes about Tailwind

These examples use the Tailwind "browser" bundle via CDN (see `<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>` in each `index.html`). That keeps these samples zero-config and easy to open. If you want to extend them in a real project, consider installing Tailwind locally and using a `tailwind.config.js` + build step.

Contributing

If you have improvements or additional examples, feel free to open a pull request. Keep each mini-project self-contained and small — the goal is easy reuse and experimentation.

License

This repository follows the license in the project root. Reuse the code freely according to that license.

