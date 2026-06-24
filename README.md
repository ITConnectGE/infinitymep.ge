# infinitymap.ge

Marketing landing page for **Infinity Map** — an independent construction consulting firm in Tbilisi, Georgia.

Static single-page site (`index.html`, no build step) served via **GitHub Pages** on the custom domain **infinitymap.ge**.

## Editing
Everything lives in `index.html` (HTML + CSS + a little vanilla JS). To update:
- **Contact details** — search for `info@infinitymap.ge`, `+995 500 00 00 00`, and `Tbilisi, Georgia` and replace with the real values.
- **Copy** — text comes in pairs: `<span data-en>…</span>` (English) and `<span data-ka>…</span>` (Georgian). Edit both.
- **Stats / numbers** — see the `.hero-meta` block.

## Local preview
Just open `index.html` in a browser, or:
```
python -m http.server 8000
```

## Deployment
Push to `main`; GitHub Pages serves the site automatically. The custom domain is pinned by the `CNAME` file.
