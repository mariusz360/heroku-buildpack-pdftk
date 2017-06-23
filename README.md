Heroku buildpack: precompiled pdftk
======================

1) Heroku supports multiple buildpacks now so just run this command:

```
heroku buildpacks:add --index 1 'https://github.com/pdfotter/heroku-buildpack-pdftk.git'
```

reference: https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app
