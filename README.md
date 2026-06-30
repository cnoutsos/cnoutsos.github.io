# Christos Noutsos — Academic Website

Static site built from your CV. No build step, no dependencies — just HTML and CSS.

## Folder contents
```
site/
├── index.html          # Home / About (landing page)
├── research.html       # Research focus & grants
├── publications.html   # Full publication list
├── teaching.html       # Teaching & mentoring
├── cv.html             # CV summary + download link
├── css/style.css       # Styling for all pages
└── assets/
    └── CV_Christos_Noutsos.doc   # Downloadable CV
```

## Preview locally
Double-click `index.html` to open it in your browser.

## Upload (pick one host)

**GitHub Pages (free)**
1. Create a repo, upload everything *inside* the `site` folder to the repo root.
2. Settings → Pages → Source: `main` branch, `/root`. Site goes live at `username.github.io/repo`.

**Netlify / Cloudflare Pages (free, drag-and-drop)**
1. Sign up, choose "Deploy manually" / "Drag and drop".
2. Drag the `site` folder in. Done.

**University web space / cPanel**
1. Upload the *contents* of `site` to your `public_html` (or `www`) folder via the file manager or FTP.

## Notes
- `index.html` must stay at the top level of whatever you upload — it's the entry page.
- To swap the CV, replace `assets/CV_Christos_Noutsos.doc` (keep the same filename, or update the link in `cv.html`). A PDF version is recommended for visitors.
