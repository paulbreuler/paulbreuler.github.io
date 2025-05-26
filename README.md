# Personal Blog Template

This repository contains a Jekyll site powered by the
[minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) theme.
It is configured for hosting on GitHub Pages and provides a simple starting
point for personal blog posts.

## Running locally

1. Install [Ruby](https://www.ruby-lang.org/en/) and
   [Bundler](https://bundler.io/).
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000` in your browser.

## Deployment

The repository includes a GitHub Actions workflow that builds and deploys
the site automatically when changes are pushed to the `gh-pages` branch.
