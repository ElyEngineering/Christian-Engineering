# Ely Christian Engineers

A faith-centered community of Christian engineers in Ely, Minnesota — men who build carefully in their craft and love faithfully in their homes.

This repo holds the public static site (HTML/CSS/JS), centered on Ephesians 5:21–33 (ESV), especially 5:25.

## Local preview

No build step. From this folder:

```bash
open index.html
```

Or serve with any static server:

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Files

- `index.html` — page structure and content
- `styles.css` — layout and design system
- `script.js` — fade-in on scroll (respects reduced motion)
- `images/` — photographs (see `images/CREDITS.md`)

## GitHub Pages

1. Push this repo to GitHub (suggested name: `ely-christian-engineers`).
2. Repo **Settings → Pages**.
3. Source: **Deploy from a branch**.
4. Branch: `main` / `/ (root)`.
5. Save. Your site will be at `https://<user>.github.io/ely-christian-engineers/`.

Do **not** use Vercel for this project; GitHub Pages is the intended host.

## Contribute

Open a pull request against `main` with small, clear changes. Keep the tone reverent, the markup accessible, and the stack static.

## Domain note

Brand targets considered: `elychristianengineers.org` (no public DNS A record at build time — likely available to register). Subdomains like `*.grok.website` are not claimable from this workflow. Register a domain at your registrar and point it at GitHub Pages when ready.

## Contact placeholder

Mailto: `hello@elychristianengineers.org` — replace with a real inbox before sharing widely.
