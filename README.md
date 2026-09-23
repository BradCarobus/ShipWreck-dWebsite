# ShipWreck-dWebsite

Website required for Apple App Store submission for **Ship Wreck'd**.

## Pages

- `index.html` — landing page
- `support.html` — support/contact info (required by App Store Connect)
- `privacy.html` — privacy policy (required by App Store Connect)
- `app-ads.txt` — authorized ad sellers file for AdMob

## Hosting

This is a static site with no build step. To host it for free with GitHub Pages:

1. Go to the repo's **Settings → Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Pick the `main` branch and `/ (root)` folder, then save.
4. Your site will be published at `https://<username>.github.io/<repo>/`.

Use that URL (and `.../support.html` / `.../privacy.html`) for the
**Marketing URL**, **Support URL**, and **Privacy Policy URL** fields in
App Store Connect.

## app-ads.txt (AdMob)

`app-ads.txt` lists the ad networks allowed to sell ads in the app. It contains
the AdMob publisher ID `pub-9446375016689596`.

AdMob only looks for the file at the **root of the domain** of the developer
website on your App Store listing. The site is deployed on Vercel at
`https://ship-wreckd-game.vercel.app/`, which serves this repo's root at the
domain root, so the file is live at
`https://ship-wreckd-game.vercel.app/app-ads.txt` once deployed to production.
