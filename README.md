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

`wrangler deploy` here. Live at https://alexdunham.net (and www), a custom
domain on the Worker via `routes` in `wrangler.jsonc`; the zone came with the
domain, bought through Cloudflare Registrar. alexdunham.alexdunham14.workers.dev
still serves it too. (alexdunham.com belongs to someone else.)

## Not done

- The intro line is a DRAFT placeholder for Alex to write.
- Three sites have no repo link: Classical Concert Map and Ireland Travel Map
  are private repos; Where Does My Tax Money Go has no GitHub repo.
