---
layout: page
title: Getting started
---

You can edit `getting-started.md` to change this page. Jekyll understands many
formats, including markdown and HTML. To change the [home page]({{ "/"
| prepend:site.baseurl }}), edit `index.html`.

You can add additional pages by copying the `new-page.html` template and edit
the `published` attribute in the front matter:

```
---
layout: default
title: Your new page
published: true
---
```


## SASS/SCSS

Jekyll uses [SASS/SCSS](http://sass-lang.com/) to create CSS. You can add your
own styles to `_sass/_custom.scss`.

Not familiar with SCSS? No problem, you can just write CSS to `assets/css/custom.css`


## Helpful resources

If you have trouble, start with the [Jekyll
documentation](https://jekyllrb.com/docs/home/) which is the main technology
behind this project.

If you’re really stuck, you can reach out to us by [opening an
issue]({{ site.jekyll_prototype_url }}) on github.
