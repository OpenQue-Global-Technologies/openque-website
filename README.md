# OpenQue Website

Marketing site for OpenQue — queue and appointment infrastructure for Indian OPDs (patient app + OpenQue AIR for hospitals/clinics). Single-page, hash-routed site with full English/Tamil support.

## Running locally

No build step. Serve the folder with any static file server and open `index.html`:

```bash
npx serve .
# or
python3 -m http.server 8000
```

Then visit `http://localhost:<port>/index.html`.

## Folder structure

```
index.html        Full site (all pages/routes, hash-based navigation)
scripts/           Runtime helpers used by the page
  support.js
  image-slot.js
assets/            Images referenced by the site
```

## Notes

- Routing is client-side via `location.hash` (`#/about`, `#/contact`, `#/legal/privacy`, etc.) — no server routes needed.
- Language toggle (English/Tamil) is handled entirely in-page; no separate localized builds.
- All content, styling, and behavior lives in `index.html`.
