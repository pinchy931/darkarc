DARKARC — deployment package
Drop the contents of this folder into the web root.

Contents:
  index.html            the site (self-contained; three.js loads from cdnjs)
  og.jpg                social share image (1200x630)
  apple-touch-icon.png  iOS/bookmark icon
  robots.txt            crawler directives
  sitemap.xml           single-page sitemap

One wiring task remains:
  The enquiry form currently opens a pre-composed mailto to hello@darkarc.co.
  To wire a backend, search index.html for "NOTE: to wire a backend"
  and replace the mailto line with a POST to your endpoint —
  the success animation already handles the rest.
