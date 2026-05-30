# ArcTimer Support Site

This repository contains the public support and privacy pages needed for App Store Connect.

## Pages

- `index.html`
- `support.html`
- `privacy.html`

## Recommended URLs

After deployment, use:

- Support URL: `https://<domain>/support.html`
- Privacy Policy URL: `https://<domain>/privacy.html`

## Deployment Options

Any static host is enough:

- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel static output
- any plain web server

No build step is required.

## GitHub Pages

This repository includes `.github/workflows/pages.yml`.

After the repository is pushed to GitHub:

1. Open the repository on GitHub.
2. Go to Settings -> Pages.
3. Set Source to "GitHub Actions".
4. Push to `main` or run the workflow manually.

The published URLs will look like:

- Support URL: `https://harutar0u.github.io/arctimer-site/support.html`
- Privacy Policy URL: `https://harutar0u.github.io/arctimer-site/privacy.html`
