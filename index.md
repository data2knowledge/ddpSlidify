---
title       : The great inventions and discoveries
subtitle    : a tale told by data
author      : data2knowledge
job         : the student on coursera
framework   : io2012   # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The great inventions and scientific discoveries

### The Goal 

The aim of this presentation is to present the Shiny application created for the course project of the Creating Data Products course in the Data Science Specialization.

### Synopsis

The great inventions and scientific discoveries explorer is based on the data of Yearly Numbers of Important Discoveries from Datasets package.

--- . Calss #id

### Data Processing


```r
library(datasets)
data(discoveries)
str(discoveries)
```

```
##  Time-Series [1:100] from 1860 to 1959: 5 3 0 2 0 3 2 3 6 1 ...
```

**discoveries** data set is the numbers of great inventions and scientific discoveries in each year from 1860 to 1959. 

### Ref:
For more information for datasetst,  click the URI below.  
(http://vincentarelbundock.github.io/Rdatasets/doc/datasets/discoveries.html)

--- . Calss #id
### The great inventions and scientific discoveries explorer
![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

To see the application, click the URI below.  
(https://data2knowledge.shinyapps.io/project/)


--- . Calss #id

### The best year of inventions and scientific discoveries

The maximum discoveries

```r
max(discoveries)
```

```
## [1] 12
```


The minimum discoveries

```r
min(discoveries)
```

```
## [1] 0
```

There were 12 discoveries in 1885 and it was the best year of inventions and scientific discoveries. And there was no discoveries in 1862, 1864, 1881, 1904, 1917, 1933, 1956, 1957, 1959.
