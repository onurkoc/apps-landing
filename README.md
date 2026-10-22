# apps-landing

Static landing page for **apps.onurkoc.net**, linking to:

- https://cv.onurkoc.net
- https://interaction-diagram.onurkoc.net
- https://groundcurve.onurkoc.net
- https://settlement.onurkoc.net

## Hosting

- Cloudflare Pages project: `apps`
- No build step (output = repository root)
- Production branch: `main`
- Custom domain: `apps.onurkoc.net`
- Caching: `_headers` sets `Cache-Control: no-cache` for `/` and `/index.html`; the Cache Rule "Pages-Apps: Header der Quelle" in zone `onurkoc.net` makes the edge respect the origin headers.
