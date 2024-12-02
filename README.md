### Editing Your Website

<https://quarto.org/docs/publishing/github-pages.html>

The `docs` directory houses the files that are ultimately hosted on your GitHub Pages instance. In order to re-render the files in the `docs` directory, run the following in terminal:

``` c
quarto render
git add docs
git commit -m "Publish site to docs"
git push
```
