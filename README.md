# Asal Meskin — Academic Homepage

A compact academic homepage built with the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme and customized for publications, research internships, honors, and academic links.

## Included in this version

- Cropped profile photograph from the supplied image
- Institution badges for EPFL, Yale, QCRI, and Sharif University
- Compact research-interest cards
- Publications with arXiv links
- Research internships with dates, supervisors, and topic tags
- Selected honors
- Responsive mobile layout and automatic dark mode

## Publish on GitHub Pages

1. Create or rename the repository to `asalmeskin.github.io`.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.

The site will be available at `https://asalmeskin.github.io/` after GitHub finishes the Pages build.

## Main files to edit

- `_config.yml`: identity, affiliation, email, profile links, SEO, and avatar path.
- `index.md`: research interests, publications, internships, and honors.
- `assets/css/style.scss`: layout, spacing, typography, logo sizes, mobile behavior, and dark mode.
- `assets/img/avatar.png`: displayed profile image.
- `assets/img/avatar-original.jpg`: original supplied photograph retained for future recropping.
- `assets/img/institutions/`: lightweight institution badges used throughout the page.

## Local preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in a browser.

## Theme credit

This repository uses [Minimal Light](https://github.com/yaoyao-liu/minimal-light), released under CC0-1.0.


## Logo note
Institution logos in `assets/img/institutions/` are included for identification on this personal academic website. They were updated to use official/logo-derived marks for EPFL, Yale, QCRI, and Sharif University of Technology.
