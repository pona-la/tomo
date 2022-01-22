# lipu-sin
sina pali e lipu sin la o kepeken lipu ni

## General HOW-TO:

1. Use [Repository Generator](https://github.com/pona-la/lipu-sin/generate) to create a new repositosiry based on this one
2. Edit the metadata in [_config.yml](https://github.com/pona-la/lipu-sine/blob/main/_config.yml) to suit your project
3. Modify [index.md](https://github.com/pona-la/lipu-sin/blob/main/index.md) to suit your site's needs, and add as many more .md and .html files as you need to expand the site

## How to build?

```bash
bundle install --path vendor/bundle
bundle exec jekyll build
```

Resulting site will be in `_site` directory.

## How to serve locally?

```bash
bundle install --path vendor/bundle
bundle exec jekyll serve
```

Visit <http://127.0.0.1:4000/> in your browser.
