# jackphilpott.github.io

Source for my portfolio website, built with [Quarto](https://quarto.org) and published to GitHub Pages.

- `index.qmd`: home page (digital CV with selected work)
- `work/`: the Work gallery (`index.qmd` reads `items.yml`) and the case studies
- `about.qmd`: about, education, languages and contact
- `styles/`: light and dark themes
- `images/`: images; `images/thumbs/` holds the 800 × 418 WebP thumbnails for the Work gallery
- `files/`: the downloadable CV (web version, no email address)

To add an item to the Work gallery, add an entry to `work/items.yml` (title, description, categories, path, image) and a thumbnail to `images/thumbs/`.

To preview locally: `quarto preview`. Pushing to `main` renders the site and publishes it to the `gh-pages` branch.

## Licence

The code in this repository (Quarto configuration, styles and scripts) is released under the MIT licence; see LICENSE. The site's text, CV and photos are not covered by that licence and may not be reused without permission. Thumbnails of REACH and FAO publications belong to their publishers and link to the originals.

Built with AI-assisted development, reviewed and tested by me. Images of maps and dashboards from the MSNA repositories use synthetic data.
