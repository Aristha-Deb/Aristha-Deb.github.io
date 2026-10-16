# Aristha Deb — Academic Website

This folder contains the HugoBlox Academic CV site customized with content from the public Google Site. It is configured for the user site repository `Aristha-Deb.github.io` and publishes at <https://aristha-deb.github.io/>.

## Publish with GitHub Pages

1. Create or open the GitHub repository named `Aristha-Deb.github.io` under the `Aristha-Deb` account.
2. Upload the **contents of this folder** to the repository root, including the hidden `.github/workflows` directory and both workflow files. No local Hugo or Node.js install is needed to publish.
3. In the repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
4. Push the files to the `main` branch. The included workflow builds the site and deploys it; check the **Actions** tab for the first run.
5. Once deployment succeeds, visit <https://aristha-deb.github.io/>.

GitHub Pages serves the site publicly. The source content is in `content/`, the profile is in `data/authors/me.yaml`, and the downloaded Google Site images are in `assets/media/images/source/`.

## Local preview (optional)

The GitHub Actions workflow installs the pinned Hugo Extended version and Node dependencies automatically. For local development, install Hugo Extended, Go, Node.js, and pnpm, then run:

```sh
pnpm install
pnpm dev
```

## Template license

HugoBlox Academic CV is distributed under the MIT License; see [LICENSE.md](LICENSE.md). The site content and images were migrated from the source Google Site.
