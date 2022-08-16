---
layout: page
title: PonzuDog
---

A [Bootstrap 4](https://getbootstrap.com/) template project for [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

- A full Bootstrap 4 theme usable both on Github Pages and with a standalone Jekyll.
- Recompiles Bootstrap from SCSS files, which allows to customize Bootstrap's variables and use Bootstrap themes.
- Full support of Bootstrap's JavaScript plugins.
- Supports all features of Github Pages and Jekyll.

## Setup Guide

### Create a repository from this template

- [Go to this repository page on Github](https://github.com/nicolas-van/bootstrap-4-github-pages).
- Click the `Star` button on the top right. (OK, this step is facultative, but that would make you a nice person)
- Click the `Use this template` button on the top right of the page.

### Choose a name for your repository

Here we have two possibilities:

- **You want a user or organization website**

  In this case your website's URL will be `http://<your username>.github.io` where `<your username>` is your Github user name.

  Choose the repository name `<your username>.github.io`.

- **You want a project website**

  In this case your website's URL will be `http://<your username>.github.io/<whatever you want>` where `<whatever you want>` can be any valid name for a Github repository.

  Choose the repository name `<whatever you want>`.

### Activate Github Pages on your repository

Go in the `Settings` page of your repository, in the `Github Pages`, under the `Source` parameter, choose `master branch` then `Save`.

### That's it

Your Github Pages website with customizable Bootstrap 4 is now up and running, you can access it using the URL displayed by Github in the `Github Pages` settings.

## Customization Guide

### Modify the configuration

You should at least edit the `_config.yml` file to edit your website's metadata, like the title, description and repository URL.

### Change your theme

This website uses the [Minty](https://bootswatch.com/minty/) Bootstrap theme by default. And you don't want to use the same theme everyone else uses do you?

You can of course modify anything in the `_includes`, `_layouts` and `_sass` folders to customize both the HTML or CSS of your website, possibly referring to the [Bootstrap documentation](https://getbootstrap.com/) or the [Jekyll documentation](https://jekyllrb.com/) when needed. This is a normal part of web development and it is outside the scope of this guide.

But if you don't know where to start I can recommend you to import a theme from [Bootswatch](https://bootswatch.com/).

- Go on [Bootswatch](https://bootswatch.com/) and choose a theme that you like.
- Using the top bar, download its `_variables.scss` and `_bootswatch.scss` files.
- Copy the content of `_variables.scss` in `_sass/_variables.scss`.
- Copy the content of `_bootswatch.scss` in `_sass/_bootstrap_customization.scss`.

That's it, you now have a totally different appearance for you website.
