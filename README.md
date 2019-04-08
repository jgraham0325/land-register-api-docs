# street-manager-docs

Welcome to the new Street Manager documentation repository.  This repo should be considered the primary source of truth for technical documentation relating to the DfT Street Manager service.

This repo will be updated and extended regularly, but will initially include the initial Street Manager API specification and business rules documentation.

Please contact the Street Manager team directly through email or Slack, should you have any queries or require additional support.

## GitHub pages

This repository contains a folder `/docs` which is intended to be served as a [Jekyll](https://jekyllrb.com/docs/github-pages/) static HTML site for serving the documentation via GitHub pages. See [here](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages) for details on setting up the repository.

### Run locally

You can clone and run the site locally to verify changes before pushing them.

**Requires:**
* [Ruby 2.1.0 or higher](https://www.ruby-lang.org/en/downloads/)
* [Bundler](https://bundler.io/) (run `gem install bundler`)

```
cd docs
bundle install
bundle exec jekyll serve # runs on http://127.0.0.1:4000/street-manager-docs/
```