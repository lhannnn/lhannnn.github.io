# Personal Academic Website

This is a first-version academic personal website for `Han Luo`, built with Jekyll for GitHub Pages.

## Local Development

Use Homebrew Ruby 3.x and Bundler:

```bash
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

Then open <http://127.0.0.1:4000>.

## Editing Content

- Site metadata: `_config.yml`
- Home page: `index.html`
- News: `_data/news.yml`
- Selected home-page publications/projects: `_data/project-main.yml`
- Project grid: `_data/project.yml`
- Publication categories: `_data/publication-category.yml`
- Publication pages: `_publication/*.md`
- CV page: `cv/index.html`

## Deployment

The included GitHub Actions workflow builds the Jekyll site and deploys it to GitHub Pages at `https://lhannnn.github.io` once this repository is published as `lhannnn.github.io`.

## Theme Credit

This site adapts [Donghoon's theme](https://github.com/donghoon-io/donghoon-io.github.io). The original theme requests credit when distributing, remixing, adapting, or building upon it.
