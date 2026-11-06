# Christol Jones portfolio

Built with Jekyll and the free [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme (MIT license).

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

## Deploy

Pushing to `main` builds and publishes the site through `.github/workflows/deploy.yml`. The address is detected automatically.

1. Create the repo on the account that will host the site. Naming it `<username>.github.io` gives the shortest address.
2. In the repo, open **Settings → Pages** and set **Source** to **GitHub Actions**.
3. Add the repo as `origin` and push `main`.

## Where things live

- Home page: `index.md`
- Project pages: `_projects/`
- About and Contact: `_pages/`
- Menu: `_data/navigation.yml`
- Name and contact links: `_config.yml`
- Photos, videos and PDFs: `assets/`
