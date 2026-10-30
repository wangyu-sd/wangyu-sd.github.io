# Yu Wang — Academic Homepage

Personal academic website: https://wangyu-sd.github.io/

Built with the [Academic Pages](https://academicpages.github.io/) Jekyll template and hosted with GitHub Pages.

## Updating content

- `_config.yml`: author name, contact details, Google Scholar, and GitHub.
- `_pages/about.md`: about, research interests, education, and internship.
- `_data/publications.yml`: **single source of truth** for Home, Publications, and CV publication lists. Add published work here; set `featured: true` for selected papers.
- `_data/navigation.yml`: top navigation.
- `_pages/cv.md`: public-facing academic CV.

Publications are curated from [Google Scholar](https://scholar.google.com/citations?user=wI8WU6kAAAAJ) and linked to official publisher/preprint records. Work not yet public is intentionally excluded.

## Portrait

The sidebar shows a "YW" monogram until a personal portrait is provided. To add one, upload `images/portrait.jpg` and set `author.avatar: "portrait.jpg"` in `_config.yml`.

## Deploy

Use GitHub Pages with the source branch `master` at `/(root)`. This repository is a Jekyll site and does not require a separate application server.

The CV LaTeX source is maintained separately and is not published here.

## Publication figure thumbnails

A small set of featured publications includes source-attributed framework diagrams, shown on both Home and Publications. They are referenced by the `image`, `image_alt`, `image_caption`, and `image_source` fields in `_data/publications.yml`.

The rendering component is `_includes/publication-card.html`, shared by both pages. Full-size images open in a new tab; other papers remain text-only. Frameworks currently use the authors' public GitHub image or figures served by the original publisher; if a publisher image becomes unavailable, the card hides the broken thumbnail rather than showing a broken icon. For long-term archival use, upload authorized figure copies to `images/papers/` and switch the `image` fields to local paths.
