# TNEB Bill Calculator

A single-file web app that estimates your Tamil Nadu Electricity Board (TNEB / TANGEDCO) electricity bill. Enter your consumed units and instantly see the estimated bill amount based on the domestic tariff slabs — all in one self-contained HTML file with zero dependencies and no backend.

## Features

- **Unit-based bill estimation** — enter consumed units, get an instant estimated bill
- **TNEB tariff slabs** — calculates using the domestic electricity tariff structure
- **Dark mode toggle** — switch between light and dark themes
- **Fully client-side** — no server, no API calls, no tracking; runs 100% in the browser
- **Single file** — the entire app is `tneb-bill-calculator.html` (HTML + CSS + JS); works offline by just opening the file
- **Responsive layout** — usable on phones, tablets, and desktops

## Tech Stack

- HTML5
- CSS3 (custom properties, dark-mode theming)
- Vanilla JavaScript

## Quick Start

Open the live site: https://girishlade111.github.io/tneb-bill-calculator/

Or run locally — no build step needed:

```bash
git clone https://github.com/girishlade111/tneb-bill-calculator.git
cd tneb-bill-calculator
# open index.html (or tneb-bill-calculator.html) in any browser
```

## Project Structure

```
├── index.html                  # live entry point (copy of the app)
├── tneb-bill-calculator.html   # the full calculator app (single file)
├── LICENSE
└── README.md
```

## Deploy

Static site hosted on GitHub Pages — any static host works (Cloudflare Pages, Netlify, Vercel). No build step.

## License

See [LICENSE](LICENSE).

---

Built by Girish Lade — https://ladestack.in
