# Theoretical Physics Website — Approved Delivery

## Project structure
- `index.html` — homepage and primary hybrid academic/practical presentation
- `about.html`, `complex-systems.html`, `teaching1.html`, `teaching2.html` — content pages
- `main.css` — shared responsive styling
- `img/` — site images
- `robots.txt` and `sitemap.xml` — crawler/SEO files
- PDF files — published academic materials referenced by the site

## Local preview / build
This is a static website and requires no compilation. From the extracted project directory, run:

```sh
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/`. Stop the server with Ctrl+C.

## Tested artifact
Git commit: `d8780d8f8749ad25ca4ec52820c1ba353ac16174`

## Validation
The exact commit passed the deterministic production snapshot, route smoke, runtime route health, internal-link, metadata, JSON-LD schema, structural-diff, exact-scope, and desktop/tablet/mobile UI-layout gates. Responsive screenshot comparison required visual inspection; the exact artifact retains its approved independent visual-review evidence. No live deployment is included in this archive.
