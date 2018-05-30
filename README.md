# WordCloud-R

## Installation
``` r
# The easiest way to get ggplot2 is to install the whole tidyverse:
install.packages("ggplot2")

# Alternatively, install just ggplot2:
install.packages("ggplot2")
```

## Cheatsheet
<a href="https://github.com/rstudio/cheatsheets/blob/master/data-visualization-2.1.pdf"><img src="https://raw.githubusercontent.com/rstudio/cheatsheets/master/pngs/thumbnails/data-visualization-cheatsheet-thumbs.png" width="630" height="252"/></a>

## Usage
``` r
library(ggplot2)

ggplot(mpg, aes(displ, hwy, colour = class)) + 
  geom_point()
```

## Getting Help
There are two main places to get help with ggplot2:

1.  The [RStudio community](https://community.rstudio.com/) is a
    friendly place to ask any questions about ggplot2.

2.  [Stack
    Overflow](http://stackoverflow.com/questions/tagged/ggplot2?sort=frequent&pageSize=50)
    is a great source of answers to common ggplot2 questions. It is also
    a great place to get help, once you have created a reproducible
    example that illustrates your problem.
