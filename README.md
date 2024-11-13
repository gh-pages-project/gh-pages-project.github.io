---
layout: page
title: GitHub pages
description: A project demonstrating how to create and deploy GitHub pages
---

GitHub pages are a static website deployed on GitHub free of charge, thanks to GitHub. The pages are used for documentation (for everything related to open source projects on GitHub) and GitHub user profiles.  In this project, we are going to learn how to create and deploy multi-repo GitHub pages under a GitHub organization, with [giscus app](https://giscus.app/) for comments. 

## 1. Setup a GitHub organization

The purpose of creating an organization is to isolate all the repos we will need in this project. You will be the only member of the organization, there is no need to add other members for now.
- Exercise: Login into your GitHub account and create a free public organization with a name of your choice, for example "gh-pages-project". For help, visit [GiHub docs](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch).

## 2. Setup a GitHub pages repo 

We have an organization, "gh-pages-project" (the org name that you picked while creating the organization), we need a repo under this organization that is necessary for deploying GitHub pages.
- Exercise: Go to your organization homepage, click on repositories, and create a new public repo with *your organization name* as the owner and the repo name "[your org name].github.io". Use "add a readme" option, for .gitignore option use jekyll, and for license use MIT license.

If all of the steps were successful, visit the address https://[your org name].github.io and --you have a website!

## 3. Add a jekyll theme

Our website layout is very basic so far. To improve it, we need to use a jekyll theme that is compatible with GitHub pages. Visit [supported themes](https://pages.github.com/themes/) to see a list of the jekyll themes we can use for this project. To use the theme, we need to create a new file at the root of our repo.

- Exercise: From homepage of your repo ("[your org name].github.io"), created a new file named _config.yml with the following content:

```
title: Home
description: Bookmark for updates!
remote_theme: pages-themes/cayman
plugins:
- jekyll-remote-theme
```
Where "cayman" is the name of the theme we want to use. You may use any of the [supported themes](https://pages.github.com/themes/).

