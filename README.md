# Ignacio Crespo Research Website

This repository contains the source for Ignacio Crespo's personal academic website:

- Production URL: `https://ignaciocr1.github.io/`
- Site type: static one-page website
- Deployment target: GitHub Pages
- Build step: none

For the persistent project context and current status, see [PROJECT_MEMORY.md](PROJECT_MEMORY.md).

## Current site structure

- `index.html`: page content, metadata, section structure, footer script
- `assets/style.css`: all styling and responsive rules
- `assets/profile.jpg`: portrait used in the header
- `assets/favicon.svg`: site favicon
- `robots.txt`: search crawler policy
- `sitemap.xml`: sitemap for the GitHub Pages URL
- `.nojekyll`: ensures GitHub Pages serves the site as plain static files

## Current content on the website

The site is currently a single landing page with these sections:

- About
- Research
- Teaching
- Contact

Research is split into:

- Working papers
- Work in progress

The current CV link in the navigation points to a Dropbox-hosted PDF, not to a file stored in this repository.

## Editing workflow

### Content updates

Edit [index.html](index.html) when you want to change:

- biography text
- research entries and abstracts
- teaching entries
- contact links
- page title and meta description

### Visual updates

Edit [assets/style.css](assets/style.css) when you want to change:

- spacing
- typography
- colors
- card styling
- mobile layout

### Metadata updates

When content changes materially, review:

- [sitemap.xml](sitemap.xml)
- [robots.txt](robots.txt)
- canonical and social metadata in [index.html](index.html)

## Local preview

Because this is a plain static site, any simple local server works. For example:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```

## Deployment

This repo is intended for GitHub Pages deployment from the repository root on the `main` branch.

Expected Pages setup:

1. GitHub repository: `ignaciocr1.github.io`
2. Branch: `main`
3. Folder: `/ (root)`

## Maintenance checklist

Use this checklist when resuming work:

1. Confirm that the content in `index.html` is current.
2. Preview the page on desktop and mobile widths.
3. Update `sitemap.xml` `lastmod` when a meaningful content change is published.
4. Check that external links still work, especially the CV link.
5. Keep [PROJECT_MEMORY.md](PROJECT_MEMORY.md) in sync with any structural or workflow changes.

## Immediate documentation status

This README was rewritten on 2026-06-25 to replace the original starter-template instructions with project-specific documentation that matches the current repository.
