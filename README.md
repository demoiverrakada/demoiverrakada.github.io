# Personal website

A plain, dependency-free personal site for Umang Agarwal: HTML and one CSS file, no JavaScript or web fonts.

## Preview locally

From this directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

- `index.html` — homepage: photo, intro, current work, all projects
- `projects.html` — all projects, grouped, with details and limits
- `research.html` — redirects to `projects.html` (kept so old links still work)
- `projects/finetune-trace.html` — Finetune Trace case study
- `about.html` — background and contact details (email shown as plain text, not a link)
- `bookshelf.html` — books, with favourites in bold and italics
- `assets/styles.css` — the only stylesheet (light and dark mode)

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
