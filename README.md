
# Danilo Croce — AcademicPages starter (Jekyll)

This is a lightweight starter you can drop **on top of** a fork/clone of
[`academicpages/academicpages.github.io`](https://github.com/academicpages/academicpages.github.io)
—or use standalone with Minimal Mistakes + jekyll-scholar.

## Quick start (private repo first, then go public)

1) **Create a private repo** on GitHub, e.g. `danilo-site`.

2) **Fork AcademicPages** (recommended) or initialize from this starter:
   - Fork: https://github.com/academicpages/academicpages.github.io → clone your fork locally.
   - Or create a new repo and copy these files in (this starter sets Minimal Mistakes + jekyll-scholar).

3) **Copy the contents** of this ZIP into your repo, overwriting files if asked.

4) Put your profile photo at `assets/img/profile.jpg` (optional).

5) Open `_config.yml` and update:
   - `url: "https://USERNAME.github.io"` → replace `USERNAME` with your GitHub username
   - check the `author.links`

6) **Add your BibTeX**: replace `_bibliography/references.bib` with your full `.bib`.

7) Commit & push.

8) **Enable GitHub Pages**:
   - Settings → Pages → Source: `GitHub Actions` (recommended) or `Deploy from branch` (if using the prebuilt `gh-pages`).
   - If you forked AcademicPages, the provided workflow will build with `jekyll-scholar`.

9) Visit `https://USERNAME.github.io`

### Update your role
You're an **Associate Professor (since September 2025)** — already reflected in the About page.
To change later, edit `_pages/about.md`.

### Colors (no B/W)
Palette is customized in `_sass/_custom.scss`. Adjust the variables at the top.

### Publications
The **Publications** page uses `jekyll-scholar` and will render from `_bibliography/references.bib`.
See `_pages/publications.md` for examples and filters.

---

## Local preview (optional)

- Install Ruby + Bundler, then:

```bash
gem install bundler
bundle init
# Add to Gemfile: jekyll, jekyll-scholar, minimal-mistakes-jekyll
bundle add jekyll jekyll-scholar minimal-mistakes-jekyll
bundle exec jekyll serve
```

Or use Docker:
```bash
docker run --rm -it -p 4000:4000 -v "$PWD":/srv/jekyll jekyll/jekyll:4   bash -lc "bundle add jekyll jekyll-scholar minimal-mistakes-jekyll && jekyll serve --watch --host 0.0.0.0"
```
