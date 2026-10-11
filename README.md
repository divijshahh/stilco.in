# Stilco static landing page

Version: 1.0.0

A responsive static landing page for Stilco / The Star Incandescent Light Co. Built with plain HTML, CSS and JavaScript. No build step or dependencies are required.

## Cloudflare Pages

1. Connect this GitHub repository in Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
2. Framework preset: **None**.
3. Build command: leave blank.
4. Build output directory: `/` or `.` if required by the dashboard.
5. Deploy, then add `stilco.in` as a custom domain and follow Cloudflare's DNS instructions.

## Before launch

- Confirm the contact email. The enquiry link currently uses `contact@stilco.in` as a placeholder; update it in `index.html` if necessary.
- Confirm the company name, brand names and historical copy.
- The product visuals are CSS illustrations rather than third-party product photos.

## Files

- `index.html`: page content and metadata
- `styles.css`: responsive visual design
- `script.js`: dynamic copyright year
- `assets/favicon.svg`: simple Stilco favicon
- `_headers`: baseline response security headers
- `robots.txt`, `sitemap.xml`: search engine discovery
