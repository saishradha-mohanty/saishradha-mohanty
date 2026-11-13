# saishradha-mohanty.github.io

Personal academic website of Saishradha Mohanty, built with [Jekyll](https://jekyllrb.com/) and a small custom layout.
Live at <https://saishradha-mohanty.github.io/>.

## Where to edit things

| What                                          | File                          |
| --------------------------------------------- | ----------------------------- |
| Name, position, email, LinkedIn, lab, menu    | `_config.yml`                 |
| Color scheme (`forest`, `plum`, `teal`, `slate`) | `palette:` in `_config.yml` |
| Home page (bio and research)                  | `index.html`                  |
| News items on the home page                   | `_data/news.yml`              |
| Awards page                                   | `awards.html`                 |
| Experience page                               | `experience.html`             |
| Photo                                         | replace `assets/img/photo.jpg` |
| Page layout (left menu, head)                 | `_layouts/default.html`       |
| Styles and palette colors                     | `assets/css/style.scss`       |

## Preview locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/>.

## Deployment

Every push to `main` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages`
branch. GitHub Pages serves that branch (**Settings → Pages → Deploy from a branch → `gh-pages`**).
