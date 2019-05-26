# `upe_mizzou.github.io`
Website for Upsilon Pi Epsilon Mizzou Chapter built with Jekyll.

## Building the Site
Ensure that [Ruby](https://www.ruby-lang.org/en/) is installed for your
platform. To install the necessary components, [Bundler](https://bundler.io/)
and the provided `Gemfile` can be used:

```sh
bundle install --path vendor
```

To build the site:

```sh
bundle exec jekyll build
```

This will build the site and output to `_site`. This can be served from any web
server, but for just testing out changes, Jekyll can serve the site for you:

```sh
bundle exec jekyll serve -I
```

The command will output the server address, which is usually `127.0.0.1:4000`.
You can visit this address from a web browser on your local machine.  The `-I`
switch enables incremental rebuilds so that the entire site does not necessarily
need to be rebuilt, but this is an experimental feature. If you run across any
issues, remove and rebuild the site from scratch:

```sh
bundle exec jekyll clean
bundle exec jekyll serve -I
```

## See Also
* [Jekyll](https://jekyllrb.com/)
* [GitHub Pages](https://pages.github.com/)
* [GitHub Pages with
  Jekyll](https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages)
