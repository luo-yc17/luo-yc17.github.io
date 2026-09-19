# Yuechen Luo — Academic Homepage

Personal academic homepage for [luo-yc17.github.io](https://luo-yc17.github.io/), built with Jekyll and GitHub Pages.

The homepage contains only three sections:

- About
- Education
- Selected Publications

Publication figures are stored locally in `images/publications/` so the page does not depend on remote image hosting. Paper, project, repository, and model links are maintained in `_pages/about.md`.

## Edit the site

- Personal and publication content: `_pages/about.md`
- Author details and sidebar links: `_config.yml`
- Navigation: `_data/navigation.yml`
- Visual design: `assets/css/main.scss`
- Avatar placeholder: `images/avatar.svg`

To use a portrait, replace `images/avatar.svg` with a photo and update `author.avatar` in `_config.yml`.

## Preview locally

```bash
bundle install
bash run_server.sh
```

Then open [http://127.0.0.1:4000](http://127.0.0.1:4000).

## Deploy

Push the repository to the `main` branch of `luo-yc17/luo-yc17.github.io`. GitHub Pages will build and publish the site automatically.

## Acknowledgements

This site is based on AcadHomepage and Minimal Mistakes. Font Awesome and Academicons are included under their respective licenses.
