heroku-buildpack-tesseract-

Added the libraries to use Tesseract 3.02.02 on Heroku

Add this git repository's url as buildpack on settings (Heroku Dashboard -> Settings -> Builpack)
```
heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi
```

```
Then creata a `Aptfile` file inside your app:
```
tesseract-ocr
```


