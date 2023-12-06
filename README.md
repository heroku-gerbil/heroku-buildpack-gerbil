# Heroku Buildpack for Gerbil Scheme

You can now deploy Heroku applications written in [Gerbil Scheme](https://cons.io)

Use this buildpack with:
```shell
heroku create myapp --buildpack heroku-gerbil/gerbil
```

See the [Heroku Example server in Gerbil Scheme](https://github.com/heroku-gerbil/heroku-example-gerbil)

## Note for the maintainer

After updating the code, I can publish it at
< https://addons-next.heroku.com/buildpacks/708e9e57-5b51-400e-82f4-6b01fb79baba/edit >
(Initially from `heroku buildpacks:register`,
see < https://devcenter.heroku.com/articles/buildpack-registry >
and < https://devcenter.heroku.com/articles/buildpacks >.)
