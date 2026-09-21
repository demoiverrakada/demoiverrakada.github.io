# Personal website

A dependency-free research portfolio for Umang Agarwal.

## Preview locally

From this directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

- `index.html` — homepage and selected work
- `research.html` — research portfolio
- `about.html` — biography and background
- `projects/finetune-trace.html` — flagship project case study
- `assets/styles.css` — responsive visual system
- `assets/site.js` — mobile navigation, reveal behavior, and reading progress

## Before publishing

- Confirm that every repository link resolves after the corresponding local project is published.
- Verify the phone number only if it will be published.
- Verify the exact Amazon role, dates, location, and externally shareable claims.
- Verify the IIT Delhi research title.
- Add a reviewed CV PDF.
- Decide which research artifacts can be made public.
- Confirm the public Finetune branch contains the same claims and reports used by this site.
- Publish the Inspect harness before enabling its repository link.
- Publish the Sandbagging result artifacts and retain the exploratory/low-FPR caveats.
- Replace the Google Fonts import with self-hosted fonts if a fully third-party-free site is preferred.

## Deployment

The site is plain HTML/CSS/JavaScript and can be deployed to GitHub Pages, Cloudflare Pages, Netlify, Vercel, or any static web server.
