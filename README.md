# Rongge Xu — Academic homepage

Personal academic website: https://ronggexu.github.io/

The current site is plain HTML and CSS in `docs/`, with no build step or JavaScript framework.

## Pages

- `docs/index.html`: profile and recent updates
- `docs/papers.html`: papers and survey articles
- `docs/talks.html`: recent talks grouped by topic, with slides and recordings
- `docs/projects.html`: research projects and teaching materials
- `docs/cv.html`: CV summary and full PDF
- `docs/assets/`: styles, photographs, CV, and slide PDFs

Edit the HTML files directly. For a new talk on an existing topic, add an item to its `talk-events` list. Link each shared slide file only once. Keep navigation consistent across pages.

## Preview

Run from this repository:

```sh
python -m http.server 8000 --bind 127.0.0.1 --directory docs
```

Then open http://127.0.0.1:8000/ or open `docs/index.html` directly.

## GitHub Pages

Publish from the `main` branch, `/docs` directory. The `.nojekyll` file keeps the site static.

The previous main branch is backed up as `backup/main-before-website-update-2026-11-07` (commit `c1431084850cb944d9b6eb8a05a92660369fd237`). The legacy Jekyll sources in `src/` are retained for reference; do not use them to overwrite the current `docs/` site.
