# Project Memory

## Purpose

This repository stores the source for Ignacio Crespo's personal academic website. It is a lightweight GitHub Pages site with no framework, no build pipeline, and no generated assets.

## Snapshot

- Project name: Ignacio Crespo Research Website
- Production URL: `https://ignaciocr1.github.io/`
- Repository role: source of truth for the published personal website
- Stack: plain HTML and CSS
- Local entry point: `index.html`
- Last documentation review: 2026-06-25

## What exists today

The website is currently a single-page academic profile with:

- an About section with biography and portrait
- a Research section with working papers, abstracts, and status badges
- a Teaching section grouped by institution
- a Contact section with email, ORCID, and LinkedIn

The design is already functional and responsive, with a simple minimalist presentation suitable for GitHub Pages hosting.

## File map

- `index.html`
  - full page markup
  - SEO metadata
  - navigation
  - research, teaching, and contact content
  - footer year script
- `assets/style.css`
  - global design tokens
  - layout rules
  - card styling
  - badge styling
  - responsive header and image sizing
- `assets/profile.jpg`
  - profile image shown in the header
- `assets/favicon.svg`
  - favicon
- `robots.txt`
  - crawler policy and sitemap location
- `sitemap.xml`
  - sitemap entries for the production URL
- `.nojekyll`
  - prevents GitHub Pages from applying Jekyll processing

## Current content notes

- The site content is real and populated, not a starter shell.
- The navigation CV link currently points to Dropbox instead of a repo-managed file.
- The canonical URL and sitemap both target `https://ignaciocr1.github.io/`.
- Research content includes working papers and one work-in-progress entry.
- Teaching content is grouped under CUNEF Universidad, BSE, and UPF.

## Current strengths

- Very small and easy to maintain
- No dependency or build maintenance burden
- Content is already structured clearly for an academic homepage
- Mobile rendering is acceptable in its current form

## Known weaknesses and cleanup opportunities

- The previous README was a generic template and did not reflect the real project state
- There was no dedicated memory file before this one
- The CV is externally hosted on Dropbox rather than stored in the repo
- The justified text style can create uneven spacing on narrow mobile screens
- `sitemap.xml` requires manual `lastmod` updates when content changes

## Recommended priorities

1. Keep documentation current before making larger content or design changes.
2. Decide whether to move the CV into `assets/` for a more self-contained site.
3. Improve typography behavior on mobile, especially justified paragraphs.
4. Continue refining research entries and outbound links.
5. Review metadata whenever the public-facing profile changes materially.

## Working conventions

- Treat `index.html` as the single source of truth for content.
- Keep styling centralized in `assets/style.css`.
- Prefer small manual edits over introducing frameworks or tooling.
- Update this file when any of the following changes:
  - site structure
  - deployment workflow
  - major content organization
  - known issues
  - next priorities

## Resume point

As of 2026-06-25, the best next step after documentation cleanup is to improve project polish:

- tighten the README and project memory first
- then refine visual/mobile details
- then review content freshness and deployment details

## Change log for memory

- 2026-06-25: Created `PROJECT_MEMORY.md` and rewrote `README.md` so repository documentation matches the actual website and current workflow.
