# Run locally

foreman start -f Procfile.dev

# Heroku
heroku buildpacks:set heroku/ruby
heroku buildpacks:add --index 1 heroku/nodejs
