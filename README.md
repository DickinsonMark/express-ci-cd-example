# Continuous Integration and Deployment with GitHub, Travis, and Heroku

[![Build Status](https://travis-ci.org/DickinsonMark/express-ci-cd-example.svg?branch=master)](https://travis-ci.org/DickinsonMark/express-ci-cd-example)

## Deploy to Heroku

1. Create app on heroku: `heroku create`
1. push to heroku: `git push heroku master`
1. add any necessary environment vairiables
1. Create db on heroku: `heroku addons:create heroku-postgresql:hobby-dev`
1. update *knexfile.js* with production config
1. push to heroku: `git push heroku master`
