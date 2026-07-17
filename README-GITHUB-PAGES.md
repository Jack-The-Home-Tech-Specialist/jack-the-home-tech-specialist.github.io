# GitHub Pages setup

This site is ready to publish as a GitHub Pages site.

## Create the repository

Create a repository in your GitHub organization named:

- jack-the-home-tech-specialist.github.io

## Push the site

From the project folder, run:

```bash
git init
git branch -M main
git remote add origin https://github.com/Jack-The-Home-Tech-Specialist/jack-the-home-tech-specialist.github.io.git
git add .
git commit -m "Initial site upload"
git push -u origin main
```

## Enable GitHub Pages

In GitHub, open the repository and go to Settings → Pages.

Choose either:
- GitHub Actions, or
- Deploy from a branch

The included workflow in .github/workflows/deploy-pages.yml will publish the site automatically when you push to main.
