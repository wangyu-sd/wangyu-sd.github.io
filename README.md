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
