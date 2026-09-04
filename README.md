# ShipWreck-dWebsite

Website required for Apple App Store submission for **Ship Wreck'd**.

## Pages

- `index.html` — landing page
- `support.html` — support/contact info (required by App Store Connect)
- `privacy.html` — privacy policy (required by App Store Connect)

## Hosting

This is a static site with no build step. To host it for free with GitHub Pages:

1. Go to the repo's **Settings → Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Pick the `main` branch and `/ (root)` folder, then save.
4. Your site will be published at `https://<username>.github.io/<repo>/`.

Use that URL (and `.../support.html` / `.../privacy.html`) for the
**Marketing URL**, **Support URL**, and **Privacy Policy URL** fields in
App Store Connect.
