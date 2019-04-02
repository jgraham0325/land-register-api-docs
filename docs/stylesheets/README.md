This site uses [govuk-frontend](https://github.com/alphagov/govuk-frontend) styles using the compiled files.

To update to a new version, download the compiled files, copy/paste the new files versions into assets/javascript/stylesheets and update the layouts to the new version filenames.

**NOTE -** You must find/replace `url(/assets` to `url(/street-manager-docs/assets` to prevent 404s caused by url paths in all CSS files for fonts/imgs.