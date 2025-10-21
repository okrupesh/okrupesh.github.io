# Simple landing page + blogs

Static site presenting my personal landing page alongside a small collection of finance-focused blog articles.

## Project Structure
- `index.html`: Hero landing page with contact links, accent color theming, and animated grain overlay.
- `blogs.html`: Blog listing page linking to individual posts.
- `assets/`: Shared imagery, backgrounds, and icons consumed across the site.
- `blogs/`: All the individual blog posts.

## Styling & Effects
- Inline CSS loads the Bebas Neue and Roboto Slab typefaces and defines the accent palette.
- A lightweight JavaScript grain effect (sourced from https://codepen.io/zadvorsky/pen/PwyoMm) adds animated texture to each page.

## Local Preview
Open any HTML file directly in a browser, or serve the site locally:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/` to explore the pages.
