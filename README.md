# Atsushi Ueda Website

This repository contains the source for my personal academic website:
[dartsushi.github.io](https://dartsushi.github.io).

The site is built with [Jekyll](https://jekyllrb.com/) and uses
[al-folio](https://github.com/alshedivat/al-folio) as a base theme, with
customized pages, styles, publication data, and research updates.

## Main Content

- Home page: `_pages/about.md`
- Publications: `_bibliography/papers.bib`
- News / recent papers: `_news/`
- CV data: `_data/cv.yml` and `assets/json/resume.json`
- Styling: `_sass/`
- PDFs and images: `assets/pdf/` and `assets/img/`

## Local Preview

### Option 1: Docker

This is the simplest way to preview the site locally:

```bash
docker compose up
```

Then open [http://localhost:8080](http://localhost:8080).

### Option 2: Native Jekyll

For a native local build you need:

- Ruby and Bundler
- Jupyter on `PATH` for notebook conversion

Then run:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at [http://localhost:4000](http://localhost:4000).

## Formatting

Prettier is used for formatting the repository.

```bash
npm install
npm run format
npm run format:check
```

If GitHub Actions reports a "Prettier Check fail", running `npm run format`
locally will usually fix it.

## Deployment

The site is hosted on GitHub Pages and deploys through GitHub Actions when
changes are pushed to the main branch.

## Notes

- This repository is the website source, not the upstream `al-folio` template.
- Some example content from the original theme is intentionally excluded from
  the built site in `_config.yml`.
