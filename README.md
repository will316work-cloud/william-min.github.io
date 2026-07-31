# william-min.github.io

Personal portfolio site for **William Min**, Technical Game Designer — live at [william-min.github.io](https://william-min.github.io).

Built as static HTML/CSS (hand-styled "corkboard / sticky notes" theme) and deployed automatically to GitHub Pages via [`.github/workflows/jekyll-gh-pages.yml`](.github/workflows/jekyll-gh-pages.yml) on every push to `main`.

## Contents

- [`index.html`](index.html) — homepage with a Projects Board and an About Me section (bio + hobbies: drawing, cooking, skiing, golfing)
- [`projects/project-buried.html`](projects/project-buried.html) — case study for **Buried in Love**, an interactive fiction dialogue system built in Unity/C#
- [`page-assets/`](page-assets/) — images used across the site, split into `front-page/` and `project-buried/`

## Development

Static site, no build step required for local editing — just open `index.html` in a browser. Pushing to `main` triggers the Jekyll GitHub Pages workflow to build and deploy.
