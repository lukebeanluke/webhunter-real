# WebHunter

A standalone website directory built with HTML, CSS, and JavaScript. No build step or backend is required.

## Publish with GitHub Pages (Jekyll)

1. Create a GitHub repository for the site.
2. Upload `index.html`, `_config.yml`, and `README.md` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select your default branch and the `/ (root)` folder, then save.
4. Open the Pages URL GitHub provides.

This is a Jekyll-compatible static site with no theme, plugin, or build dependency. Jekyll will publish the root `index.html` directly.

## Adding websites

Use the **Add website** button in the app. Additions are saved in local browser storage on that device. For additions to appear for every visitor, click **Export my additions**, then incorporate the exported JSON records into the `roundTwoSites`/site data in `index.html` and commit the updated file to GitHub. Browser-only JavaScript cannot write commits to your GitHub repository automatically without a separately configured, authenticated backend.

## Notes

The built-in directory contains the prior 500 entries plus 500 new entries, including 200 new gaming listings. External destinations may change or become unavailable; review unfamiliar websites before visiting.
