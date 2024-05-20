# Anshuman Singh

[![pages-build-deployment](https://github.com/anshumansingh1/anshumansingh1.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/anshumansingh1/anshumansingh1.github.io/actions/workflows/pages/pages-build-deployment)

### Made with passion using github pages

Link: [https://anshumansingh1.github.io/](https://anshumansingh1.github.io/)

> [!IMPORTANT]
> Actual site development yet to start.

## Steps to create a new jekyll project
1) Install Jekyll: `gem install jekyll bundler`
2) Check Jekyll version: `jekyll --version`
3) Create new Jekyll site: `jekyll new anshumansingh1.github.io`
4) Move to the new directory: `cd anshumansingh1.github.io`
5) Build locally using: `bundle exec jekyll serve --livereload`

## Steps to host this site to GitHub pages using continuous deployment
1) Goto *Settings > Code and automation > Pages > Build and deployment* : Change **Source** under **Build and deployment** from **Deploy from a branch** to **GitHub Actions**
2) Goto *Actions* tab.
3) Create new **Jekyll** workflow, review and commit changes.
4) Done, now we can edit/create new post and it will be automatically be build and deployed.
