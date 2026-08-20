# Personal Knowledge Vault — Landing Page

A simple responsive static landing page for "Personal Knowledge Vault" — a concept product for structured note-taking and a second brain. This repository contains the HTML, CSS, and image assets for the page.

## Stack
- Language(s): HTML, CSS
- Runtime: Static site (no build step)
- Notable assets: hero background and UI icons in the `assets/` folder

## What you'll find
```
index.html           # Main static HTML file (entry point)
styles/style.css     # Page styling
assets/              # Images and icons used by the UI
Sections/            # Example section screenshots / design images
UI/                  # Additional UI mockups
```

## How to view locally
Open the page directly in your browser or run a tiny local server from the repository root.

Option 1 — open file
- Double-click `index.html` or open it from your browser: `file:///path/to/index.html`

Option 2 — quick local HTTP server (recommended for correct asset loading)
- Python 3.x:

  python3 -m http.server 8000

Then open http://localhost:8000 in your browser.

- Node (http-server):

  npm install -g http-server
  http-server -p 8000

## Development notes
- The page uses Inter font (loaded from Google Fonts) and Font Awesome via CDN; you need internet access to load those.
- Editing `index.html` and `styles/style.css` is the main way to change layout and styling.
- Large images live in `assets/` (hero-bg.png, Home.png, Section images). Optimize them if you need faster load times.

## Suggestions / next steps
- Add a license (e.g., MIT) if you want others to reuse the code.
- Add a small build step (e.g., PostCSS/image optimization) if you plan to deploy publicly.
- Add a live demo via GitHub Pages by enabling Pages in the repository settings and pointing to the root branch.

## Contributing
Small changes are welcome — open issues or PRs for fixes, optimizations, or content updates.

---
*README created by GitHub Copilot assistant — I inspected `index.html`, `styles/style.css`, and the `assets/`, `Sections/`, and `UI/` directories to summarize the project.*
