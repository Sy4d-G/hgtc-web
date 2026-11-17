# HGTC 2026

Landing page for HIMTIKA Goes to Company, highlighting the visits to Blu by BCA Digital and Hacktiv8.

## Run locally

Open `index.html` directly or serve this directory with any static web server, for example:

```powershell
python -m http.server 5173
```

The page uses Tailwind CSS from its CDN and the Google Fonts stylesheet declared in `index.html`.

## Deploy

This is a static site. Import the repository in Vercel with the project root set to `/`, framework preset set to **Other**, and no build command. The output directory can be left empty/default because `index.html` is at the repository root.

## Assets

Only files referenced by the page are included in `assets/`. Temporary inspection files and local logo-reference working files are intentionally excluded.
