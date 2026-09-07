# alexdunham.net

A list of Alex Dunham's websites: name, link, one factual sentence, and a link
to the GitHub repo where the repo is public. Nothing else.

## Definition of done

- One page at alexdunham.net listing every live site, each with a link, a
  sentence on what it is, and a repo link where the repo is public.
- Plain HTML and a few lines of CSS. No JavaScript, no data file, no build
  step: nine entries do not need one.
- Adding a site is one `<li>` in `index.html` and a `wrangler deploy`.

## Deploy

`wrangler deploy` here. alexdunham.net is bought through Cloudflare Registrar,
so the zone exists with the domain. Once it does, uncomment `routes` in
`wrangler.jsonc` and deploy again. Until then the site is at
alexdunham.alexdunham14.workers.dev. (alexdunham.com belongs to someone else.)

## Not done

- The intro line is a DRAFT placeholder for Alex to write.
- Three sites have no repo link: Classical Concert Map and Ireland Travel Map
  are private repos; Where Does My Tax Money Go has no GitHub repo.
- The Ireland map has no domain; it links to its workers.dev address.
