# Ferrite Engineering — Public Website

Public-facing static site for Ferrite Engineering, served via GitHub Pages.

This is the **public-lean** site: it establishes that the company is real, keeps the
"modernizing the EDA toolchain" and open-source positioning, names no products, and
carries a short generic founder bio. The richer internal version (full founder bio,
product detail) lives in the private `ferrite-website` repo.

## Stack

- Plain HTML / CSS / vanilla JS — no build step
- Previewable via `file://` or `python3 -m http.server`
- Deployed by GitHub Pages from the repo root on `main`

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

```
ferrite-website-public/
├── index.html        # Landing page
├── about.html        # Founder page (short bio + contact)
├── 404.html
├── robots.txt
├── css/              # reset, tokens (brand), base, components, pages/
├── js/main.js        # nav toggle + current year
└── img/              # logos + favicon
```
