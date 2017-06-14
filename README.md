Strange Case
============

Strange Case is a template for presentations using [Jekyll](https://jekyllrb.com/) and [Reveal.js](http://lab.hakim.se/reveal-js)


## Getting Started

Download the latest Strange Case
```
git clone git@github.com:chrishalebarnes/strange-case.git my-presentation
cd my-presentation
```

Install and configure [rbenv](https://github.com/rbenv/rbenv) and [ruby](https://www.ruby-lang.org/) if it's not already installed

Fetch the depdencies
```
bundle install && npm install
```

Change `baseurl`, `url`, `repository`, and `title` in `_config.yml` to the appropriate values for your presentation.

Run the Jekyll server
```
bundle exec jekyll serve
```

Visit `localhost:4000/my-presentation` in a browser!

Note that `my-presentation` is the title from `_config.yml`.

Finally you can get started writing [Markdown](https://daringfireball.net/projects/markdown/syntax) in `slides/0-introduction.md`

## GitHub Pages

For deployment to GitHub Pages the dependencies need to be available, so `node_modules` needs to be removed from `.gitignore` and pushed to the `gh-pages` branch.

## License and Copyright

See [LICENSE](https://github.com/chrishalebarnes/strange-case/blob/master/LICENSE)
