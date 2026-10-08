# Foundations of Clinical Research: course website

**Live site:** <https://neu-data.github.io/FoundationsofClinicalResearch/> (English: `/en/` · Tiếng Việt: `/vi/`)

<p align="center"><img src="en/images/course-poster.png" alt="Course poster" width="520"></p>

The bilingual website of the Neudata course *Foundations of Clinical Research: From Clinical Question to
Publication* (8 Saturdays · one session per week · 24 contact hours), with trainers Vương Mỹ Lượng & Bernard Osang'ir.

This repository only holds the **generated website sources**. The course materials and the generator
(`site/build.py`) live in a private Neudata repository. Do not edit the files here by hand. Instead, change the
course sources, run `python site/build.py` there, and copy the contents of `site/_publish/` here.

| Folder | What it is |
|---|---|
| `en/`, `vi/` | Quarto website projects (English, Vietnamese): pages, revealjs slide decks, figures and downloads |
| `_shared/` | Landing page (`index.html`, asks for the language), theme, language switch, access gate, Neudata slide extension |
| `.github/workflows/publish-site.yml` | Renders both sites with Quarto and publishes them to GitHub Pages |

Publishing: **Settings → Pages → Build and deployment → Source: GitHub Actions**. Every push to `main` re-publishes.
Preview locally with `quarto preview en` (or `vi`).

All materials are free; the pages ask for a free access code once per browser (we only count users).
FLUID-ICU is a **simulated** teaching dataset.

---
Neudata Consulting Ltd · *Insight. Impact. Innovation.* · [www.neu-data.com](https://www.neu-data.com)
