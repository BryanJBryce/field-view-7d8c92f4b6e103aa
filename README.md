# Phase 1 proposal page

A one-page static proposal for Craig Bloomfield from Bryce Labs LLC.

Plain HTML and CSS. No build step, no JavaScript, no external requests.

## Files

- `docs/index.html` — all page content
- `docs/styles.css` — layout and styles
- `docs/.nojekyll` — tells GitHub Pages to serve the files as-is

## View locally

```sh
python3 -m http.server 8000 --directory docs
```

Then open <http://localhost:8000/>.

## Publishing

To publish, serve the `docs/` folder from `main` with GitHub Pages
(Settings → Pages → Deploy from a branch → `main` → `/docs`).

On GitHub Free, Pages requires a public repository, so the page and this
repository's files are publicly readable. The page carries
`noindex,nofollow` to discourage search indexing; that does not restrict
access.

All figures shown on the page are invented examples.
