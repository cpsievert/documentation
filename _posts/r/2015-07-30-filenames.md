---
title: R Filenames, Folders, and Updating Plotly Graphs in R | Examples | Plotly
name: Filenames, Folders, and Updating Plotly Graphs in R
permalink: r/file-options/
description: How to update your graphs in R with the fileopt parameter.
layout: base
language: r
page_type: example_index
has_thumbnail: false
display_as: file_settings
---

# Setting Filenames and Overwriting Plotly Graphs in R




```r
library(plotly)
```

By default, if you don't specify a filename,
printing `plot_ly` will create a new plot in your online plotly account.


```r
plot_ly(x = c(1, 2), y = c(1, 2))
```

<iframe height="600" id="igraph" scrolling="no" seamless="seamless" src="https://plot.ly/~RPlotBot/533.embed" width="800" frameBorder="0"></iframe>
<br>
If you want to overwrite the plot and keep the graph served from the same plotly URL, specify a filename.
This implicitly overwrites your plotly graph.
View your Plotly graphs at [https://plot.ly/organize](https://plot.ly/organize).


```r
plot_ly(x = c(1, 2), y = c(1, 2), filename="name-of-my-plotly-file")
```

<iframe height="600" id="igraph" scrolling="no" seamless="seamless" src="https://plot.ly/~RPlotBot/505.embed" width="800" frameBorder="0"></iframe>
<br>
If the filename contains "/", it will automatically create a plotly folder.


```r
plot_ly(x = c(1, 2), y = c(1, 2), filename="r-docs/name-of-my-plotly-file")
```

<iframe height="600" id="igraph" scrolling="no" seamless="seamless" src="https://plot.ly/~RPlotBot/507.embed" width="800" frameBorder="0"></iframe>