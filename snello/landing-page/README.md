# Snello landing page

`snello.html` is a Jekyll source page published at `/snello/` through its
permalink. Keep it in this folder; no copying or extra build step is needed.
The homepage links to it from Selected work.

The page reuses `/assets/css/portfolio.css` for the site's colors, typography,
header, buttons, and footer. `/assets/css/snello.css` adds responsive product
layouts. Screenshots live in `/assets/images/snello/` and remain unchanged.
All local links and assets use `relative_url` to support GitHub Pages base URLs.
The shared SEO include supplies canonical, Open Graph, and Twitter metadata;
the page is included in the site's sitemap.

Edit the front matter for the title and description, and the page body for
product copy. The primary call to action points to Google Play for the
`io.snello.app` package. Remove the "Coming soon to Google Play" notice once
the listing is published. The private source repository is not linked.
Privacy and terms links point to the existing Snello policy pages.

Publish with the repository's existing GitHub Pages process. The `_site/`
directory is generated output and does not need manual edits.
