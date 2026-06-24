# infinitymep.ge

Site for **Infinity MEP** — independent MEP (mechanical / electrical / plumbing) engineering & construction consulting in Tbilisi, Georgia.

Served via **GitHub Pages** on the custom domain **infinitymep.ge** (no build step).

## Current landing page — interactive CAD drawing
`index.html` is a text-free, full-screen **interactive AutoCAD/ArchiCAD-style site plan**:
- Pan (drag empty space), zoom (mouse wheel), CAD crosshair + live coordinate readout.
- **Move** any element (trees, shrubs, car, bench, lamps), **rotate** a selected element via its handle, hold **Shift** to snap rotation to 15°.
- **Building**: drag to move, drag corner grips to resize — the dimension lines update live (metres). Movement snaps to a 0.5 m grid.
- Toolbar (top-right, icon-only): reset view · toggle grid · toggle dimensions. `Esc` deselects.

All vanilla HTML/SVG/JS, single file, no dependencies.

## Previous version
`landing-classic.html` — the earlier bilingual (EN / ქართული) text landing page, kept for reference.

## Local preview
Open `index.html` in a browser, or `python -m http.server 8000`.

## Deployment
Push to `main`; GitHub Pages serves automatically. Custom domain pinned by `CNAME`.
DNS import file for Cloudflare: `dns/infinitymep.ge.zone`.
