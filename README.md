# Personal website

A plain, dependency-free personal site for Umang Agarwal: a single HTML page with inline CSS, no frameworks or web fonts.

## Preview locally

From this directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

- `index.html` — the whole site: intro, now, questions, timeline, projects, honors, contact (styles inline, light and dark mode)
- `404.html` — shown for any other path, links back to the homepage
- `assets/umang.jpg` — profile photo
- `assets/grokking_curve.png` — figure for the grokking reproduction

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

## Deployment

The site is plain HTML/CSS and can be deployed to GitHub Pages, Cloudflare Pages, Netlify, Vercel, or any static web server.
