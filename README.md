# Dubois & Co.

Static site for [duboisco.ca](https://duboisco.ca), served by GitHub Pages. There's no build step.

| Page | EN | FR |
| --- | --- | --- |
| Home | `index.html` | `fr/index.html` |
| About | `about.html` | `fr/a-propos.html` |
| Companies | `companies.html` | `fr/entreprises.html` |
| Brand kit | `brand.html` | — |

- Shared styles and brand tokens: `assets/css/site.css`
- Logo files (full, horizontal, mark, plus paper-coloured reverses): `assets/logo/`. The full lockup comes in FR (`dubois-logo-full`) and EN (`dubois-logo-full-en`). The SVGs are the masters; the PNGs are 2× exports of them
- Original raster logo (legacy, superseded by the SVGs): `duboislogo.png`

The brand kit at [duboisco.ca/brand.html](https://duboisco.ca/brand.html) is the reference for logo use, colour, type, voice, downloadable assets and CSS tokens.

Preview locally with `python3 -m http.server` and open http://localhost:8000.
