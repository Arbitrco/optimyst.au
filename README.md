# Optimyst website

Marketing site for **Optimyst**, a fictional field-service software company used as the demo organisation in [Ketsudan](https://ketsudan.co) product demos. Optimyst and Reid Refrigeration are not real businesses. Names, sites, figures and people on the site are illustrative.

## What's here

| Path | What |
| --- | --- |
| `index.html` | The whole site: one self-contained page, no build step |
| `favicon.svg` | The gauge mark |
| `assets/logos/` | Gauge mark and horizontal lockup, light and dark |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

Fonts load from Google Fonts (Bricolage Grotesque, IBM Plex Sans, IBM Plex Mono). Everything else is inline.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. The site appears at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

To use your own domain, add it under **Settings → Pages → Custom domain**. GitHub creates the `CNAME` file for you.

## Editing

Edit `index.html` directly. Colours are CSS variables at the top of the file, with dark mode values below them. The brand rules (voice, colours, type, logo use) live in the Optimyst design system.

The page has `noindex` set so search engines don't list a fictional company. Remove that meta tag if you want it indexed.
