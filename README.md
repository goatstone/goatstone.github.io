# goatstone.github.io

Source for [goatstone.com](https://goatstone.com), the web development portfolio of Jose Collas.

A static site of plain HTML and CSS. There is no build step and no dependencies.

## Structure

- `index.html`: home page
- `work.html`: featured work
- `certifications.html`: certifications
- `contact.html`: contact details
- `style.css`: shared styles
- `images/`: site images
- `sitemap.xml`, `robots.txt`: search engine files
- `CNAME`: custom domain for GitHub Pages

## Local preview

Serve the folder with any static file server:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deployment

GitHub Pages serves the `main` branch from the repository root at https://goatstone.com. Merging to `main` publishes the site.
