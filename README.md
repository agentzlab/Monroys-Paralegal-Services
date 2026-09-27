# Monroy's Paralegal Services

> **Reliable paralegal support for busy attorneys** — filing, legal documentation, and overflow contract work, done right and on time.

![Pages](https://github.com/agentzlab/Monroys-Paralegal-Services/actions/workflows/pages/pages-build-deployment/badge.svg)
![Last commit](https://img.shields.io/github/last-commit/agentzlab/Monroys-Paralegal-Services)
![Repo size](https://img.shields.io/github/repo-size/agentzlab/Monroys-Paralegal-Services)
![Static site](https://img.shields.io/badge/site-static-blue)

**Live preview:** https://agentzlab.github.io/Monroys-Paralegal-Services/

> **Note:** this is the *template/demo* site for Maria Monroy's new company, built in the agentzlab org to gather her feedback. It is distinct from the Next.js production build in Jon's Vader fleet (`D:\Hermes\projects\Monroys-Paralegal-Services`).

![Dark-mode hero — current build](assets/screenshot.png)

## What's inside

- `index.html` — single-file template site (design adapted from a harvested GetLayers prompt, copy written for a paralegal-services audience, generated placeholder imagery throughout)
- `assets/screenshot.png` — current dark-mode screenshot of the page
- `.nojekyll` — GitHub Pages static serving
- `docs/reference.md` — source links and research pointers
- `docs/CURSOR-BLUEPRINT.md` — build notes for Cursor/Vader

## Design language

Deep, professional dark theme with gold accents — trust and prestige without the generic law-firm beige. Editorial serif headlines, generous whitespace, real photography-style generated imagery (office, documents, filing), never flat icon grids.

## Tech stack

| Layer | Choice |
|---|---|
| Markup | Single self-contained `index.html` |
| Styling | Hand-written CSS, no framework |
| Motion | Light scroll reveals, no heavy WebGL on this one |
| Imagery | AI-generated plates (template holders until Maria supplies real photos) |
| Hosting | GitHub Pages from `main` |

## Project structure

```
Monroys-Paralegal-Services/
├── index.html
├── assets/
│   └── screenshot.png
├── docs/
│   ├── reference.md
│   └── CURSOR-BLUEPRINT.md
└── .nojekyll
```

## Workflow

Changes land on branches, never straight to `main`. No pull requests unless Jon asks — he reviews the branch (or the artifact preview) and says when to merge. GitHub Pages serves `main`, so `main` is always the presentable version.
