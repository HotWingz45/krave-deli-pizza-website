# Krave Deli & Pizza — Website

One-page website for **Krave Deli & Pizza**, the 24-hour deli, pizza spot, and smoothie bar at 1399 2nd Ave, Upper East Side, NYC.

## What's inside

- `index.html` — the entire site. Fully self-contained: all styles, scripts, and fonts (Anton + Oswald, embedded as data URIs) live in this one file. No build step, no dependencies.

## Hosting

Upload `index.html` to any static host and you're live:

- **GitHub Pages** — in the repo settings, enable Pages from the `main` branch root.
- **Netlify / Vercel / Cloudflare Pages** — point at this repo, no build command needed.
- **Any web host** — drop the file in the public folder.

## Editing

Everything is in `index.html`:

- **Menu items & prices** — search for `The Board`; each item is a `<li>` with a name, dotted leader, and price. Deli and Fresh Bar prices match the official café menu; pizza prices are still estimates (Krave Pizza's menu wasn't available).
- **Phone number** — search for `6469645256` (appears in `tel:` links and the schema block).
- **Address / map links** — search for `1399`.
- **Colors** — the palette is defined once in the `:root` block (`--brick`, `--kraft`, `--mustard`, etc.).

## Facts baked in

- Open 24 hours, 7 days
- (646) 964-5256
- 1399 2nd Ave, New York, NY 10021
- 4.7★ · 150 Google reviews (update these as they grow)
