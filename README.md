# How To Use MathJax With Minima
I implemented the following steps to be able to write LaTex whilst using the default Minima theme:

1) Create an empty file in the root of your repo called `_includes/head.html`.
2) Run `bundle info minima` to find the location of the minima gem files.
3) Copy the contents of the `_includes/head.html` file from the minima theme into the file created in Step 1. 
4) Add the following just before `<\head>`:

```
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML" async>
</script> 
```

_In general you can follow these [instructions](https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll#customizing-your-themes-html-layout) to customise a jekyll theme._
