# Plainview–Old Bethpage Soccer Club website

Static site built with [Jekyll](https://jekyllrb.com/) and served by GitHub Pages.

## Editing content

Each page is an HTML file at the repo root with YAML frontmatter at the top:

```yaml
---
layout: page
title: "Contact Us"
lead: "The preferred method of communication is email."
section: Info
---
```

Edit the content below the frontmatter, commit, and push — GitHub Pages rebuilds automatically.

**Quick edits:** open any `.html` file on GitHub and click the pencil icon to edit in your browser.

## Site structure

- **`_config.yml`** — site settings and navigation menu structure
- **`_layouts/`** — page templates (home page and interior pages)
- **`_includes/`** — shared components (nav, footer)
- **`assets/`** — CSS, JS, images, and documents
- **`*.html`** (root) — page content files

## Adding or removing a page

1. Create a new `.html` file at the repo root with the frontmatter above
2. Add the page to the `nav` section in `_config.yml`

## Preview locally

```bash
bundle exec jekyll serve
```

Then open http://localhost:4000.
