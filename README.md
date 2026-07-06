# Zheyuan Lin — Academic Profile

Source for the concise academic site at <https://martylinzy.github.io/academic/>.

The site uses [Academic Pages](https://github.com/academicpages/academicpages.github.io), Jekyll, and GitHub Pages. The separate personal blog remains at <https://martylinzy.github.io/>.

## Content

- `_pages/about.md`: homepage
- `_publications/`: publication records
- `_portfolio/`: project records
- `_pages/cv.md`: concise CV
- `_data/navigation.yml`: top navigation
- `_config.yml`: site and author metadata

## Local preview

Docker is the recommended local environment:

```bash
docker compose build
docker compose up
```

Open <http://localhost:4000/academic/>.

To build without starting the preview server:

```bash
docker compose run --rm jekyll-site bundle exec jekyll build
```

## Deployment

Pushes to `master` trigger `.github/workflows/pages.yml`. The workflow builds the Jekyll site and deploys `_site/` to GitHub Pages.

The repository's Pages source must be set to **GitHub Actions** in GitHub Settings → Pages.

## License

The site template is based on Academic Pages and remains available under the MIT License; see `LICENSE`.
