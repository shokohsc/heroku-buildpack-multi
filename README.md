# heroku-buildpack-multi

Use multiple buildpacks on your app

## Usage

    $ heroku config:add BUILDPACK_URL=https://github.com/shokohsc/heroku-buildpack-multi.git

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#0198c71daa8
    https://github.com/heroku/heroku-buildpack-ruby.git#v86
