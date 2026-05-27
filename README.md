# Personal research website (GitHub Pages)

This folder contains a minimal, one-page static website you can publish with GitHub Pages (no build step).

## Quick start (recommended): user/organization site

1. Create a repo named **`<your-username>.github.io`** (or `<org>.github.io`) on GitHub.
2. Copy the contents of this `research-site/` folder into the repo root.
3. Commit + push to `main`.
4. In GitHub: **Settings → Pages** → set **Source** to **Deploy from a branch** and choose **Branch: `main` / `(root)`**.

Your site should be available at `https://<your-username>.github.io/`.

Example for you: create `ignaciocr1.github.io` → your site will be `https://ignaciocr1.github.io/`.

## Alternative: project site

If you publish from a normal repo (e.g. `my-research-site`), GitHub Pages will serve it under
`https://<your-username>.github.io/<repo>/`. This template uses relative links, so it works in both modes.

## Customize

- Update your name/affiliation/bio: `index.html`
- Add your papers / teaching / contact: `index.html`
- Put your CV PDF at `assets/cv.pdf`
- Update styling: `assets/style.css`

## Optional: custom domain

If you use a custom domain, add a `CNAME` file at the site root with your domain name on a single line
and configure DNS in your domain provider.
