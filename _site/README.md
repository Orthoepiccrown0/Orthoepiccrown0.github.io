# Dmytro Zyatikov's portfolio

Static Jekyll portfolio and Android developer résumé, hosted on GitHub Pages at
https://public.orthoepiccrown.org.

## Search metadata

English copy is maintained in `_data/portfolio.yml` and `_data/resume.yml`.
The two pages share `_includes/seo.html`; the résumé also renders ProfilePage
structured data from its visible profile content.

`url` and `production_url` in `_config.yml` must match the public HTTPS domain.
The separate `production_url` keeps canonical and sitemap URLs stable when
`jekyll serve` changes `url` to localhost. Keep `baseurl` empty for this domain.

The homepage and résumé opt into the sitemap with `sitemap: true`. Configuration
defaults also include the existing Bento and Snello policy pages. Add the same
front matter flag to future public pages that should appear in the sitemap.

## After deployment

1. Confirm the published homepage, `/resume/`, `/robots.txt`, and `/sitemap.xml`
   are available on the configured HTTPS domain.
2. Open [Google Search Console](https://search.google.com/search-console) and
   verify ownership of the domain or its HTTPS URL-prefix property using the
   instructions provided there.
3. In **Sitemaps**, submit `https://public.orthoepiccrown.org/sitemap.xml`.
4. Use **URL inspection** for the homepage and résumé to request indexing, then
   review indexing status and search performance after Google has processed them.

These repository changes do not deploy the site or submit anything to Search
Console. Indexing and search positions are determined by search engines.
