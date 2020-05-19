# [Harry Jackson's personal site](https://harrychowjackson.github.io)

built on [Agency Jekyll theme](https://github.com/y7kim/agency-jekyll-theme), Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

====================

# How to use
With any luck, no one but me will be reading this, so it's for my own future reference more than anything. If you are reading this, then enjoy your stay poking around my repos and please don't judge me.

## Local testing

In short, every github account is allowed one free site at \[username\].github.io, built from a repository of the same name. [harrychowjackson.github.io](https://harrychowjackson.github.io) uses Jekyll, according to `_config.yml`, to build a lightweight site from all the contents of this repo (note, only from the branch named `master`!).

The public site might take a few minutes to update when changes are made to this repository. In order to test updates, it's much faster to clone this repository, host the site locally, make your changes, and then commit when satisfactory.
 
`git clone https://github.com/harrychowjackson/harrychowjackson.github.io`

`cd harrychowjackson.github.io`

`bundle exec jekyll serve`

Then open [localhost:4000](http://localhost:4000) in your favorite browser to see the site.

## Updating this site
`git add .`
`git commit -m "\[descriptive message here\]"`
`git push origin master`

## Template
Thanks to `y7kim`, view the original jekyll template theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

====================

For more details, read [jekyll documentation](http://jekyllrb.com/)
