---
title: Getting Started with Plotly in R
name: Getting Started with Plotly in R
permalink: r/getting-started/
description: Get started with Plotly's R graphing library to make interactive, publication-quality graphs online.
page_type: example_index
layout: base
language: r
---



# Plotly for R

Plotly is R package for creating interactive web-based graphs via [plotly](https://plot.ly/)'s JavaScript graphing library.

<a href="https://travis-ci.org/ropensci/plotly">
    <img alt="Build Status" style="margin: 0;" src="https://travis-ci.org/ropensci/plotly.png?branch=master">
</a>

#### Installation

__plotly__ is not (yet) available on CRAN, but you can install it via [devtools](http://cran.r-project.org/web/packages/devtools/):

```r
devtools::install_github("ropensci/plotly")
```


#### Signup

If you don't already have a plotly account, either [signup online](https://plot.ly/how-to-sign-up-to-plotly/) or use the `signup()` function (see the `help(signup)` page for more details).

Note you can check if you have a username and API key with:

```r
plotly:::verify("username")
plotly:::verify("api_key")
```

#### Credentials

Find your credentials [in our online settings](https://plot.ly/settings/api). Set them in your R session with:

```
Sys.setenv("plotly_username"="your_plotly_username")
Sys.setenv("plotly_api_key"="your_api_key")
```

<div class="row centered btnrow">
    <a href="/r/" class="button no_underline">view examples</a>
</div>
