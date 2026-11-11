# apps-landing

Static landing page for **apps.onurkoc.net**, linking to:

- https://cv.onurkoc.net
- https://interaction-diagram.onurkoc.net
- https://groundcurve.onurkoc.net
- https://shear.onurkoc.net
- https://settlement.onurkoc.net
- https://joints.onurkoc.net

## Hosting

- Cloudflare Pages project: `apps`
- No build step (output = repository root)
- Production branch: `main`
- Custom domain: `apps.onurkoc.net`
- Caching: `_headers` sets `Cache-Control: no-cache` for `/` and `/index.html`; the Cache Rule "Pages-Apps: Header der Quelle" in zone `onurkoc.net` makes the edge respect the origin headers.

## Design and fonts

Style follows https://cv.onurkoc.net (grid, white / black / red, Inter Tight). Inter Tight is self-hosted in `fonts/` (latin subset, SIL OFL, licence in `fonts/OFL-InterTight.txt`); no third-party font requests. Dark theme uses the same red hue, lightened for contrast.
