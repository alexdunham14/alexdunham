# alexdunham.com

A list of Alex Dunham's websites: name, link, one factual sentence, and a link
to the GitHub repo where the repo is public. Nothing else.

## Definition of done

- One page at alexdunham.com listing every live site, each with a link, a
  sentence on what it is, and a repo link where the repo is public.
- Plain HTML and a few lines of CSS. No JavaScript, no data file, no build
  step: eight entries do not need one.
- Adding a site is one `<li>` in `index.html` and a `wrangler deploy`.

## Deploy

`wrangler deploy` here. Until alexdunham.com is added as a zone on the
Cloudflare account (nameservers pointed at Cloudflare), the site is at
alexdunham.alexdunham14.workers.dev; then uncomment `routes` in
`wrangler.jsonc` and deploy again.

## Not done

- The intro line is a DRAFT placeholder for Alex to write.
- Two sites (Classical Concert Map, Ireland Travel Map) are private repos, so
  they have no repo link.
- The Ireland map has no domain; it links to its workers.dev address.
