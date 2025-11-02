# Seismic Hub

Seismic Hub is a lightweight static site / landing page for Seismic — a privacy-powered fintech blockchain focused on private, compliant DeFi primitives and developer tooling.

This repository contains a simple HTML/CSS landing page (index.html) that presents Seismic's value proposition and links to developer resources and community channels.

## Contents

- `index.html` — Static landing page built with plain HTML/CSS (responsive, hero, features, about, footer).
- `README.md` — This file.
- (Add other assets or docs as you iterate.)

## Features

- Dark, modern hero with gradient and SVG grid background
- Clear CTA linking to GitHub org and Discord
- Sections: Features, About, Contact
- Responsive layout for mobile and desktop
- Smooth-scrolling navigation

## Usage

Serve the site locally with any static server or by opening `index.html` in the browser.

Examples:

- Open directly:
  - Double-click `index.html` or open in browser: file://.../index.html
- Using Python 3 (simple local server):
  - python3 -m http.server 8000
  - Open http://localhost:8000

## Development

- Edit `index.html` to change copy, links, or styling.
- Styles are inline inside `<style>` in the HTML for quick iteration; consider extracting to `styles.css` for larger changes.
- To add images or other assets, create an `assets/` folder and reference them from the HTML.

## Suggestions / Next Steps

- Extract CSS to a separate stylesheet and add build tooling (npm, Tailwind/PostCSS) if you plan to expand the site.
- Add accessibility improvements (aria labels, keyboard navigation checks).
- Add tests or CI to lint HTML/CSS and validate links.
- Add a small README section for contribution guidelines and license.

## Contact

For partnership or developer inquiries:
- Email: fintech@seismic.systems
- Discord: https://discord.gg/seismicsys
- GitHub: https://github.com/SeismicSystems

---

Copyright © 2025 Seismic Community Hub