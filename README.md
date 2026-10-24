# rukitis.id.lv

Digital playground placeholder. Static files only, deployed as a Cloudflare Worker with static assets.

- `public/` is everything that gets published. `index.html` is the live page.
- `versions/` holds the other designs. They are not published. To switch, copy one over `public/index.html`.
- `public/_headers` sends `X-Robots-Tag: noindex` on every response, so the site stays out of search engines.
- Font: Host Grotesk, SIL Open Font License (see `public/fonts/OFL.txt`).

Deploy: push to `main`. Cloudflare runs `npx wrangler deploy`.
