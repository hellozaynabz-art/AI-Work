# Zaynab Product AI Portfolio

This repository is configured to publish a static portfolio with GitHub Pages.

## Deployment

1. Add the exported portfolio files to the repository root. The site entry point
   must be named `index.html`.
2. In the GitHub repository, open **Settings → Pages** and select **GitHub
   Actions** as the source.
3. Push to `main` or `work`, or run the **Deploy to GitHub Pages** workflow
   manually from the Actions tab.

The workflow uploads the repository as a static Pages artifact and publishes it
using GitHub's official Pages actions.

## Current limitation

The source preview at
`https://zaynab-product-ai-portfolio.zzennour2018.chatgpt.site/` requires
authorization from this environment, so its HTML and assets are not included in
this repository. Export the site from ChatGPT and add those files before
deploying.
