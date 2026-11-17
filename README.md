# OmniLabs LLC — GitHub Pages placeholder

A lightweight, responsive, single-file static website. No packages, frameworks, or build steps required.

## Publish on GitHub Pages

1. Create a GitHub repository (for example, `omnilabs-site`).
2. Upload `index.html` and `.nojekyll` to the repository root and commit.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. GitHub will publish at `https://YOUR-USERNAME.github.io/omnilabs-site/` after deployment completes.

## Use a custom domain

In **Settings → Pages**, enter your custom domain and follow GitHub's DNS instructions. Enable **Enforce HTTPS** once the certificate is ready. Do not use a domain you do not control.

## Customize

- `index.html`: All page copy and styling are in this file.
- RustyRMM link currently points to `https://rustyrmm.com/`.
- Update company name/legal wording if needed before publication.
- The year in the footer updates automatically.

## Technical details

Pure HTML/CSS with a tiny JavaScript year update. No external dependencies, tracking, analytics, fonts, or images. Works from the root or a GitHub Pages project subpath.
