# Search App
This is a freshly generated Blacklight application, built using the [Quickstart](https://github.com/projectblacklight/blacklight/wiki/Quickstart) instructions, but with [blacklight_lando](https://github.com/bess/blacklight_lando) instead of solr_wrapper.

## Running locally
1. Checkout this code base
2. `asdf install`
3. `bundle install`
4. `yarn install`
5. `lando start` to start solr + postgres
6. `bundle exec rails s` to start rails server

You should now be able to see the application at http://localhost:3000
