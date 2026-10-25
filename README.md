# Alan's Website

This repository contains the source for Alan's GitHub Pages website and its supporting demos.

## Website entry points

- [Digital Ace home](./index.html) — main website landing page.
- [Digital Transformation home](./home.html) — the original transformation portal.
- [All pages](./pages/index.html) — directory of the standalone pages grouped under `pages/`.

## Project structure

- `pages/` — standalone site pages, technology/process details, and demos.
- `assets/` — shared stylesheets, scripts, fonts, and other site resources.
- `images/` — site images grouped by category, including `people/`, `process/`, and `technology/`.
- `documents/` — downloadable awards, certificates, and resumes.
- `videos/` — video assets.
- Other root folders — separate projects and demos such as `python/`, `ML/`, `OCR/`, `tableau/`, and `webAPIcall/`.

The root `index.html` is kept in place as the GitHub Pages entry page. Use the navigation on either home page or the [All pages](./pages/index.html) directory to reach the site's pages.

## Publishing

The site is published with GitHub Pages. To publish committed changes, push them to the branch configured in the repository's Pages settings:

```powershell
git add -A
git commit -m "Describe your changes"
git push origin main
```

Replace `main` with the configured publishing branch if it differs.
