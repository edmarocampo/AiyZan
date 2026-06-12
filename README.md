# AIYZAN Intelligence — Website

Multi-page static site. No build step, no dependencies — all CSS is inlined in each page.

## Deploy to GitHub Pages (3 steps)
1. Create a repo (e.g. `aiyzan-website`) and upload **ALL files in this folder** —
   the 5 HTML files **and the entire `assets/` folder** (drag the whole folder in,
   or use "Add file → Upload files" and include the folder).
2. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder: `/ (root)`.
3. Wait ~1 minute. Site appears at `https://<username>.github.io/aiyzan-website/`

Important: `index.html` must sit at the repo ROOT (not inside a subfolder).

## Files
- index.html / services.html / portfolio.html / about.html / contact.html
- assets/ — images only (logo + dashboard photos). CSS is already inside each page.
- .nojekyll — tells GitHub Pages to serve files as-is.

## Editing
Contact email, links, and text are plain HTML — edit in any text editor.
