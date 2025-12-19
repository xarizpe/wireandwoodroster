# WireAndWoodRoster.com (Static Site)

A lightweight static site for **Wire & Wood Roster**.

## Pages
- `index.html` — Home (The Convergence)
- `roster.html` — The Roster (Artists)
- `process.html` — The Process (Wire & Wood Philosophy)
- `contact.html` — Contact (The Label)

## Image placeholders
All required images live in `assets/images/` as **SVG placeholders** you can replace with your final artwork/photos.

Recommended replacements:
- `hero-split.svg` → final hero image (1920×1080)
- `lyric-tablet.svg` → secondary image (approx 1400×900)
- `mateo-portrait.svg`, `silas-porch.svg`, `drayven-road.svg` → square roster portraits (1200×1200)
- `process-xlr-tree.svg` → process image (1600×900)
- `footer-horizon.svg` → footer panorama (2000×600)

You can replace the SVGs with PNG/JPG by keeping the **same filename** (or update the `<img src>` paths in the HTML).

## Deploy
### GitHub Pages
1. Create a repo (e.g., `wireandwoodroster`)
2. Upload these files to the repo root
3. In GitHub: **Settings → Pages → Deploy from branch** → select `main` and `/ (root)`

### Any web host
Upload the folder contents to your site root (where `index.html` lives).

## To customize
- Styles: `assets/css/style.css`
- Small JS helper: `assets/js/main.js`
- Update emails and social links in `contact.html`
- Update the Drayven “Pre-Save” URL in `roster.html`

---
Managed by Rodolfo Arizpe
