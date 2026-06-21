# XyC0212.github.io

Personal academic homepage of **Xiangyu Chen** — Ph.D. student at the MARS Lab, Nanyang Technological University.

Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Content map

| What | Where |
| --- | --- |
| Bio / home page | `_pages/about.md` |
| News | `_news/announcement_*.md` |
| Publications | `_bibliography/papers.bib` |
| CV (rendered) | `_data/cv.yml` (+ `_pages/cv.md`) |
| CV PDF | `assets/pdf/cv.pdf` (replace the placeholder) |
| Identity / site config | `_config.yml` |
| Social & contact links | `_data/socials.yml` |
| Profile photo & paper previews | `assets/img/` |

## Local development

```bash
gem install bundler
bundle install
npm install
bundle exec jekyll serve
# open http://localhost:4000
```

## Deployment

This site is built and deployed by GitHub Actions (`.github/workflows/deploy.yml`),
which publishes the built site to the `gh-pages` branch.

**One-time setup:** In the GitHub repo, go to **Settings → Pages → Build and deployment**
and set the source to **GitHub Actions** (or "Deploy from a branch → `gh-pages`").
al-folio cannot be built by GitHub's default `github-pages` gem, so this step is required.

---

Theme: [al-folio](https://github.com/alshedivat/al-folio) by Maruan Al-Shedivat and contributors (MIT License).
