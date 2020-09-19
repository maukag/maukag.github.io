# How To Use Mathjax With Minima

1) Run `bundle info minima` to find the location of the minima gem files.
2) Copy the `_includes/head.html` file from the minima theme into the root of the current repo. Then add
the following just before `<\head>`:

```
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML" async>
</script> 
```

_In general you can follow these [instructions](https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll#customizing-your-themes-html-layout) to customise a jekyll theme._
