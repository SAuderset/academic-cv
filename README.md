# Personal website of Sandra Auderset

Built with [Hugo](https://gohugo.io/) and the
[HugoBlox academic-cv](https://github.com/HugoBlox/hugo-theme-academic-cv)
theme. No AI tooling is used: the files in this repository are edited
by hand and the site is built and deployed by GitHub Actions
(`.github/workflows/`) on every push to `main`.

## Structure
- `content/`          - all pages (publications, talks, research, teaching)
- `config/_default/`  - site configuration (params.yaml, menus.yaml, ...)
- `data/authors/me.yaml` - your profile shown on the homepage
- `assets/media/`     - images (avatar: `assets/media/authors/me.jpg`)
- `static/uploads/`   - files served as-is (CV: `static/uploads/resume.pdf`)

## Edit and publish
1. Edit the Markdown files (locally or on github.com)
2. Commit and push to `main`
3. GitHub Actions rebuilds and deploys the site automatically
