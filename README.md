# Avyaan Corp — Website

A single-page site styled with an Apple-inspired hero and typography, paired
with Material You–inspired color, shape, and elevation.

## Files
- `index.html` — page structure and content
- `styles.css` — all styling, including light/dark mode (follows the visitor's system setting)
- `script.js` — the mobile navigation menu

## Publish it on GitHub Pages
1. Create a new repository on GitHub (e.g. `avyaan-website`).
2. Upload `index.html`, `styles.css`, and `script.js` to the root of the repository.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
6. GitHub publishes the site in a minute or two, at
   `https://<your-username>.github.io/<repository-name>/`.

## Customize
- Contact details live in the **Contact** section near the bottom of `index.html`.
- Colors, radii, and fonts are CSS variables at the top of `styles.css`
  (`--color-primary`, `--color-accent`, etc.) — change them there and they
  update everywhere.
- "Avyaan" appears in the header and footer of `index.html` — I assumed this
  as the display name from the `avyaancorp@gmail.com` address; rename it if
  that's not right.
