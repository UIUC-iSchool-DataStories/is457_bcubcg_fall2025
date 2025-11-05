# Course Template

## How to install and use locally

1. Step 1: to clone this repo locally
2. Step 2: [install Jekyll](https://jekyllrb.com/docs/installation/) (scroll down for OS-specific instructions)
3. Step 3: cd into the local repo's directory
4. Step 4: install bundles with `bundle install`
5. Step 5: host locally with `bundle exec jekyll serve` and navigate to the URL with the repo's name in it that is printed out with this command
6. Step 6: edit text files as needed to update slides, config, course data, etc
7. Step 7: push changes to remote and wait for site to rebuild on the web (go to "Actions" tab on GitHub for progress)

## Step up Course for new semester



### Basic Info

This repository is a template for managing coursework using GitHub pages.  It
uses the theme [dinky](https://github.com/pages-themes/dinky),
[nbviewer.js](https://github.com/kokes/nbviewer.js), and
[reveal.js](https://revealjs.com/) for presenting material.

For each week of class, create a subdirectory `weekZZ` (where `ZZ` is the week
of the class) and place any `.ipynb` and `.md` files in that directory.
Lectures can utilize the layout `lecture`, which will present them in revealjs.
