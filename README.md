# Heroku Buildpack for Gerbil Scheme

You can now deploy Heroku applications written in [Gerbil Scheme](https://cons.io)

Use this buildpack with:
```shell
heroku create myapp --buildpack fare/gerbil
```

See the [Heroku Example server in Gerbil Scheme](https://github.com/heroku-gerbil/heroku-example-gerbil)

## Note for the maintainer

After updating the code, I can publish it at
< https://addons-next.heroku.com/buildpacks/ca13e561-bcff-4482-b78f-7a7ebc1adf37/publish >
(Initially from `heroku buildpacks:register`,
see < https://devcenter.heroku.com/articles/buildpack-registry >
and < https://devcenter.heroku.com/articles/buildpacks >.)

TODO: Next time, make our own Debian- or Ubuntu- based package that already includes sqlite?
