SMastroianni Website
====================

Agency theme based on [Agency bootstrap theme](http://startbootstrap.com/templates/agency/)

# Instructions

This website is built using [Jekyll](http://jekyllrb.com/), which aids in building static webpages using a templating approach.

Assuming a OS X environment you need to install the `jeykll` gem.

    gem install jekyll

This will give you access to the `jekyll serve` command, which will allow you to view/develop the website locally. After executing this command you can visit `http://127.0.0.1:4000/` to view the website. As long as the `jekyll serve` command is running any changes you make will be reflected in the browser (although you have to manually refresh the page).

Simply pushing the new changes to github will deploy the website from its *jeykell* state.

# Jekyll Structure

## HTML

The `_layouts` directory specifies the layotus for to *constructing* the website. A `default.html` layout is provided which is applied to the index page, which imports the specified files from the `_includes` directory. Thus it is simple to add a new *html* file to the `_includes` directory, and simply *include* it in the `_layouts/default.html`.

## Misc.

### Portfolio

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

### About

Images are in '/img/about/'

### Team

Team members and info are in '_config.yml'

Images are in '/img/team/'
