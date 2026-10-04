# Geyi Yang — Academic Website

Source for [garyyang12345.github.io](https://garyyang12345.github.io), built with Jekyll and GitHub Pages.

## Content structure

- `_pages/about.md` — homepage content and section ordering
- `_pages/projects/` — project detail pages
- `assets/css/site.css` — all site-specific styling
- `_sass/` and `assets/css/main.scss` — Academic Pages theme foundation
- `_data/navigation.yml` — top navigation
- `images/` — profile, organization, and project media
- `files/GeyiYang_CV.pdf` — CV linked from the homepage and navigation

## Local development

```bash
bundle install
bundle exec jekyll serve
```

The local site is normally available at `http://127.0.0.1:4000/`.

## Build check

```bash
bundle exec jekyll build
```

Generated output is written to `_site/` and should not be edited directly.

## Updating content

1. Edit homepage copy in `_pages/about.md`.
2. Add or revise detail pages in `_pages/projects/`.
3. Put referenced media in `images/` using descriptive filenames.
4. Replace `files/GeyiYang_CV.pdf` whenever the CV changes.
5. Run a local build and check desktop and mobile layouts before deployment.

The site-specific layer is intentionally kept separate from the inherited theme: use `assets/css/site.css` for visual changes and avoid adding one-off rules to `assets/css/main.scss`.
