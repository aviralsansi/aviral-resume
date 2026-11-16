# Aviral Sansi — Marketing Portfolio

A responsive, single-page portfolio built with HTML and CSS. It includes the supplied profile photo and Instagram performance snapshot as embedded image assets, so no separate asset hosting or build step is needed.

## Live site

Once GitHub Pages is enabled for this repository, the expected URL is:

**https://aviralsansi.github.io/aviral-resume/**

## Deployment

This repository includes `.github/workflows/deploy.yml`. Every push to `main` (and manual workflow dispatch) runs the GitHub Actions workflow and publishes the site to GitHub Pages.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Open the **Actions** tab and check the latest **Deploy portfolio to GitHub Pages** run.
4. When the run succeeds, open the live site URL above.

The workflow uses the official GitHub Pages actions and requires no repository secrets.

## Updating the portfolio

Edit `index.html` and commit the change to `main`. The workflow will redeploy automatically. The portfolio is plain HTML/CSS, so there is no npm install or build command.

## Repository note

This repository is currently private. GitHub Pages availability for a private repository depends on the GitHub plan. To make the portfolio publicly viewable on a plan that only supports Pages for public repositories, change the repository visibility to **Public** in **Settings → General → Danger Zone**. Review the repository contents before changing its visibility.
