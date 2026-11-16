# Constance de Taillac — CV website

A responsive static website based on the CV in the project root. The site source is in [`site/`](site/).

## GitHub Pages deployment

The workflow in [`.github/workflows/pages.yml`](.github/workflows/pages.yml) deploys the contents of `site/` when changes are pushed to `main`. It can also be started manually from the repository’s **Actions** tab.

To publish:

1. Create a GitHub repository and connect this local repository to it as the `origin` remote.
2. Push the `main` branch.
3. In the GitHub repository, open **Settings → Pages** and set the source to **GitHub Actions** if it is not already selected.
4. Check the **Actions** tab for the deployment run and use its Pages URL.

No build step or external packages are required.
