This is a [hugo](http://gohugo.io/) [caladown](https://djnavarro.github.io/hugo-calade/) site

## Basic operation (hugodown)

If the site is created with [hugodown](http://hugodown.r-lib.org/)

* Preview the site with `hugodown::hugo_start()`; it will automatically
  update (navigating to the latest change) as you modify `content/`.

* Create a new post bundle with `hugodown::use_post('post/short-title')`.

## Basic operation (blogdown)

If the site is created with [blogdown](https://github.com/rstudio/blogdown)

* Preview the site with `blogdown::serve_site()`

* Create a new post with `blogdown::new_post()`
