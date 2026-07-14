# Asal Meskin — Academic Homepage

A compact academic homepage built with the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme.

## Publish on GitHub Pages

1. Create or rename the repository to `asalmeskin.github.io`.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.

The site will be available at `https://asalmeskin.github.io/` after GitHub finishes the Pages build.

## Main files to edit

- `_config.yml`: name, affiliation, email, profile links, SEO, and avatar path.
- `index.md`: page content, publications, internships, and honors.
- `assets/css/style.scss`: spacing, typography, cards, mobile layout, and dark-mode refinements.
- `assets/img/avatar.png`: replace this monogram with a square profile photo using the same filename.

## Local preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in a browser.

## Theme credit

This repository uses [Minimal Light](https://github.com/yaoyao-liu/minimal-light), released under CC0-1.0.
