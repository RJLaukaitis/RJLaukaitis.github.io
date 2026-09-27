# RJLaukaitis.github.io

Marketing site for apps and projects by RJ Laukaitis, styled like a mid-2000s online auction site.

Plain static HTML/CSS served by GitHub Pages — no build step.

| Route | File |
| --- | --- |
| `/` | `index.html` — product listings |
| `/tile-wizard/` | `tile-wizard/index.html` — TileWizard item page |
| `/privacy/` | `privacy/index.html` — privacy policy covering all apps |

## Adding a new app

1. Copy `tile-wizard/` to `your-app/` and edit the content.
2. Add a row to the listings table in `index.html`.
3. Add an entry under "App-Specific Details" in `privacy/index.html` and bump the "Last Updated" date.
