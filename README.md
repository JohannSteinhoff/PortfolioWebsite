# Johann Steinhoff — Portfolio

**Live site:** https://johannsteinhoff.github.io/PortfolioWebsite/

A single-file personal portfolio site (HTML + CSS + JavaScript), rebuilt from the
original Framer site so it can be hosted and edited independently.

## Files
- `index.html` — the entire website. Open it in any browser; no build step required.

## Editing
All content lives in `index.html`. Edit the text directly in the relevant
`<section>`. Design tokens (colors, fonts, radius) are CSS variables in the
`:root` block near the top of the file.

## Hosting
Works as static hosting anywhere — GitHub Pages, Netlify, Vercel, or any web
server. For GitHub Pages: Settings → Pages → deploy from `main` / root.

## Notes
- Images load from Framer's CDN (`framerusercontent.com`) and fonts from Google
  Fonts. To become fully independent, download the images into a local folder
  and update the `src` URLs.
