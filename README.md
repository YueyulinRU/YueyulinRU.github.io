# YueyulinRU.github.io

Personal academic homepage, built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme, deployed via GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

The site is then available at `http://localhost:4000`.

## Content

- `_pages/about.md` - homepage bio
- `_pages/cv.md` + `_data/cv.yml` - CV
- `_bibliography/papers.bib` - publications list
- `assets/img/prof_pic.jpg` - profile photo

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it to GitHub Pages.
