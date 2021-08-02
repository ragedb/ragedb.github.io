# ragedb.github.io
Github Page for [RageDB](https://ragedb.com)

### Instructions

This page uses [Jekyll](https://jekyllrb.com/) and the [Bulma](https://bulma.io) CSS Framework.

GitHub Pages will automatically serve the site, but to test locally you can:

    gem install bundler
    bundle update
    bundle exec jekyll serve --livereload

To make style changes:

Modify sass/ragedb_styles.scss with your modifications and rebuild css:

    sass --sourcemap=none sass/ragedb_styles.scss:css/ragedb_styles.css

For additional help see:
    - [Jekyll Docs](https://jekyllrb.com/docs/)
    - [Bulma with sass gem](https://bulma.io/documentation/customize/with-sass-cli/)
