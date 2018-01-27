> This starter kit is **not maintained**. I'd suggest instead checking out [this article](https://simpleit.rocks/how-to-add-bootstrap-4-to-jekyll-the-right-way/), or if you want an example of a github pages jeykll repo using bootstrap 4 (not using a gem as GH pages doesn't support that) check out [this repository](https://github.com/JavaScript-NZ/nzjscon-website/tree/master/_sass).

# Bootstrap 4 + Jekyll

To use: when you have the dependancies as per
[the docs](https://jekyllrb.com/docs/installation/) you should run
`bundle install`.
    
HTML files are based on Minima - if you need to configure
the post or page layouts, copy [those files](https://github.com/jekyll/minima/tree/master/_layouts) in as needed.
    
Bootstrap variables can be overriden in `_sass/custom.scss` - refer
to the [full list of available values](https://github.com/twbs/bootstrap/blob/v4-dev/scss/_variables.scss).

Note that GitHub Pages doesn't run gems that aren't on their predefined list, so it won't work with their autocompile, you'll need to push up and serve the compiled files.
