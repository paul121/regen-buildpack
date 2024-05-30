# regen-buildpack

A [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) that makes the `regen` and `jq` binaries available to your app.

Use [multiple buildpacks](https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app) to use this alongside your application language.

Add the buildpack:

```
heroku buildpacks:add https://github.com/paul121/regen-buildpack.git
```
