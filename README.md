# Denis Vojťuk — professional CV

The source for [denis.vojt.uk](https://denis.vojt.uk), published through GitHub Pages.

A responsive, static CV for a Senior Engineering Manager, covering engineering
leadership, backend software, cloud infrastructure, distributed systems and open source.

## Files

- `index.html` — complete page content, responsive styling and search metadata.
- `assets/Denis_Vojtuk_CV.pdf` — the downloadable one-page CV.
- `favicon.ico` — browser favicon at 16, 32 and 48 pixels.
- `favicon-96x96.png` — square favicon for browsers and search results.
- `apple-touch-icon.png` — 180-pixel icon for saved shortcuts on Apple devices.
- `assets/icon-512.png` — reusable 512-pixel DV icon.
- `assets/social-preview.png` — 1200 × 630 PNG used when sharing the site.
- `robots.txt` — crawler access rules and the sitemap location.
- `sitemap.xml` — the canonical home page and its last significant update date.
- `assets/fonts/` — self-hosted IBM Plex Sans, weights 400, 500 and 600. See
  `assets/fonts/OFL.txt` for the font license.
- `CNAME` — the existing custom domain, `denis.vojt.uk`.
- `.nojekyll` — serves the static files without a Jekyll build.

The page requires no package installation, build step or third-party font service.
Content, section navigation and the PDF download work without JavaScript. A small
inline script adds a temporary highlight after anchor scrolling and restarts it
on repeated navigation. Scrolling and highlights respect reduced-motion settings.
Mobile screens use a single column; desktop screens show experience alongside
expertise, projects and education. Print styles are included; the download is the
fixed one-page version.

## Editing and preview

Edit `index.html` directly. Keep the website and downloadable PDF consistent when
updating experience or achievements. The displayed update month is maintained
manually.

For a local preview, run `python3 -m http.server 8000` from this directory and open
`http://localhost:8000`. Check both a desktop and a narrow mobile viewport before
publishing. GitHub Pages publishes the configured `master` branch.

## Search and sharing metadata

Keep the title, meta description, Open Graph and Twitter metadata consistent with
the visible CV when changing the role, location or professional summary. The
JSON-LD graph describes the website, profile page and person; preserve its stable
`@id` values and update factual fields together with the visible content. Do not
use the DV icon as `Person.image`; that field is reserved for a real profile image.

Use `https://denis.vojt.uk/` as the canonical home-page URL. Add only canonical
page URLs to the sitemap, not section fragments, icon files or the downloadable
PDF. Update `lastmod` after substantive content or structured-data changes, not
automatically on every deployment. Keep the sitemap URL in `robots.txt` correct
and allow crawlers to access the page and its images.

Keep favicon URLs stable. When changing the branding, regenerate the icon sizes
and the social preview together; ensure the declared image dimensions and alt
text match the files. After publication, check the icon and preview URLs, validate
the JSON-LD and sitemap, and use Search Console to inspect indexing when needed.

Reference documentation:

- [Google: title links](https://developers.google.com/search/docs/appearance/title-link)
- [Google: profile-page structured data](https://developers.google.com/search/docs/appearance/structured-data/profile-page)
- [Google: favicons](https://developers.google.com/search/docs/appearance/favicon-in-search)
- [Google: sitemaps](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap)

## Brand assets

The icon and social preview were created with the built-in image-generation tool.
The final icon brief was: "A bold, white DV monogram on a flat, opaque dark-blue
#174e70 square, with thick strokes and clean counters readable at favicon size;
no gradients, shadows or extra symbols."

The preview brief was: "A white 1200 × 630 editorial card with Denis Vojťuk,
Senior Engineering Manager, Prague, Czechia and denis.vojt.uk on the left,
and the DV mark on the right; charcoal text and a dark-blue accent."

Published PNG and ICO files are resized exports of those generated assets.
The reusable icon is `assets/icon-512.png`.

## Contact

- Email: [denis@vojt.uk](mailto:denis@vojt.uk)
- LinkedIn: [denis-voytyuk](https://linkedin.com/in/denis-voytyuk/)
- GitHub: [denisvmedia](https://github.com/denisvmedia)
