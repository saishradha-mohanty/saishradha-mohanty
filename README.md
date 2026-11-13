# saishradha-mohanty

Personal academic website, built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## Where to edit things

| What                                       | File                                                  |
| ------------------------------------------ | ----------------------------------------------------- |
| Name, site URL, global settings            | `_config.yml`                                         |
| Home page (bio, research/papers)           | `_pages/about.md`                                     |
| Awards page                                | `_pages/awards.md`                                    |
| Experience page (industry, teaching)       | `_pages/experience.md`                                |
| Profile photo                              | replace `assets/img/prof_pic.jpg` (keep the filename) |
| Email / LinkedIn / Scholar / GitHub links  | `_data/socials.yml`                                   |

Navbar order is set by `nav_order` in each page's front matter.

More customization options: [docs/CUSTOMIZE.md](docs/CUSTOMIZE.md).

## Preview locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/>.

## Deployment

Every push to `main` runs `.github/workflows/deploy.yml`, which builds the site and pushes the result to the `gh-pages` branch.

One-time setup on GitHub:

1. **Settings → Actions → General → Workflow permissions**: select **Read and write permissions**.
2. After the first workflow run finishes, **Settings → Pages → Build and deployment**: Source = **Deploy from a branch**, Branch = **`gh-pages`** / `(root)`.

The site is served at <https://saishradha-mohanty.github.io/>. This requires the repository to be named `saishradha-mohanty.github.io` (with `baseurl:` empty in `_config.yml`).
