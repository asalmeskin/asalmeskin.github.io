# Asal Meskin — Academic Portfolio

A responsive, single-page academic website designed for GitHub Pages.

## Files

- `index.html` — all website content
- `styles.css` — layout, responsive design, dark/light themes, and animations
- `script.js` — theme switching, mobile navigation, active sections, and reveal effects
- `.nojekyll` — tells GitHub Pages to serve the site as a plain static website

## Publish on GitHub Pages

### Personal root address

For a site at:

```text
https://asalmeskin.github.io
```

your GitHub username must be `asalmeskin`, and the repository must be named:

```text
asalmeskin.github.io
```

If your username remains `asalmskin`, use:

```text
asalmskin.github.io
```

and the website address will be:

```text
https://asalmskin.github.io
```

### Upload instructions

1. Create the correctly named public repository.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`.
6. Save.

## Before publishing

Search in `index.html` for the following details and confirm them:

- Yale internship dates: currently shown as `Remote · Ongoing`
- MLBIO project description
- QCRI project wording
- Email and profile links
- Publication status

## Customize

Most text is directly editable in `index.html`.

The main visual settings are at the top of `styles.css` under `:root`. Change variables such as:

```css
--purple: #9b87f5;
--cyan: #66e3ff;
--pink: #ff7dd8;
```

No build tool is required.
