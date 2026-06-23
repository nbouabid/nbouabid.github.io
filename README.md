# Nermine Bouabid — Academic Website

Static site for GitHub Pages. **Home page = `index.html`.**

## Files
- `index.html` — Home (landing page)
- `about.html` — About / Research / Talks / Codes / Teaching / Honors / Memberships
- `support.js` — runtime (required; keep it next to the HTML files)
- `assets/` — images and the presentation PDF
- `robots.txt` + `<meta name="robots" content="noindex,nofollow">` — keep the site out of search engines
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Publish (simplest way)
1. Create a new GitHub repository, e.g. `yourusername.github.io` (or any repo name).
2. Upload **everything inside this folder** to the repository root (keep the `assets/` folder structure).
3. In the repo: **Settings → Pages → Build and deployment → Source: "Deploy from a branch"**, select `main` and `/ (root)`, then Save.
4. Wait ~1 minute. Your site is live at `https://yourusername.github.io/` (or `.../repo-name/`), opening on the Home page.

## Notes
- Search engines are asked not to index the site (robots meta + robots.txt). This is a request, not a hard block — anyone with the link can still view it.
- To update content, edit `index.html` / `about.html` and re-upload.
