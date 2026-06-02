# Workshop Slides — Building Your Academic Website in 1 Hour

Slides for the [Hacking Communication Science](https://hackingcommsci.org) workshop.
Built with [Quarto](https://quarto.org) RevealJS and hosted on GitHub Pages.

## View the slides

The rendered slides are in the `docs/` folder and served via GitHub Pages.

## Edit the slides

All content is in `index.qmd`. Render locally with:

```bash
quarto preview
```

Or render to `docs/` for deployment:

```bash
quarto render
```

## Deploy

The `docs/` folder is committed to the repo and served directly by GitHub Pages
(Settings → Pages → Deploy from branch → `main` → `/docs`).
After running `quarto render`, commit and push `docs/` to update the live slides.

## Structure

- `index.qmd` — all slide content
- `_quarto.yml` — Quarto + RevealJS configuration
- `custom.scss` — slide theme overrides
- `docs/` — rendered output (do not edit manually)
- `*.png` — images used in the slides
