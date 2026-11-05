# Element Snap landing page

A static site: `index.html` plus the `images/` folder. No build step.

## Publish on GitHub Pages

1. Create a new repository on github.com (for example `element-snap`). On a free plan, make it **Public**.
2. On the empty repository page choose **uploading an existing file**, then drag in everything inside this folder:
   `index.html`, `images/`, `README.md` and `.nojekyll`. Commit.
3. Open **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**,
   branch **main**, folder **/ (root)**, and click **Save**.
4. Wait a minute or two, then refresh the Pages settings. The address appears at the top:
   `https://<your-username>.github.io/element-snap/`

To update later, upload the changed files to the same repository; the site redeploys on its own.

## Before going live

- The Download buttons and "Full change log" link are inert placeholders (`href="#" data-inert`).
  Swap in real links and remove `data-inert` when you have them.
- For link previews on Slack or X, change `og:image` in the `<head>` to the full address,
  e.g. `https://<your-username>.github.io/element-snap/images/og-hero.png`.

Fonts load from Google Fonts. The Chrome mark comes from Simple Icons (CC0).
