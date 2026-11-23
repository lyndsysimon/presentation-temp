# Presentation

A [Slidev](https://sli.dev/) deck, published as a static site on GitHub Pages.

## Local development

- `pnpm install`
- `pnpm run dev`
- visit <http://localhost:3030>

Edit [slides.md](./slides.md) to change the slides.

## Deploy

Pushing to `main` builds the deck and deploys it to GitHub Pages via
[.github/workflows/deploy-pages.yml](./.github/workflows/deploy-pages.yml).
The workflow can also be started manually from the Actions tab.

Published at <https://lyndsysimon.github.io/presentation-temp/>.

Preview the production build locally:

```
pnpm run build --base /presentation-temp/ --out dist
```
