
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rminkav3

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/Development-BioMarine/rminkav3/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/Development-BioMarine/rminkav3/actions/workflows/R-CMD-check.yaml)
[![CRAN
status](https://www.r-pkg.org/badges/version/rminkav3)](https://CRAN.R-project.org/package=rminkav3)
[![Codecov test
coverage](https://codecov.io/gh/Development-BioMarine/rminkav3/graph/badge.svg)](https://app.codecov.io/gh/Development-BioMarine/rminkav3)
<!-- badges: end -->

The goal of rminkav3 is access Minka observations through the API.

## Installation

You can install the development version of rminkav3 from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("Development-BioMarine/rminkav3")
```

## Usage

It’s hard to succinctly describe how ggplot2 works because it embodies a
deep philosophy of visualisation. However, in most cases you start with
`ggplot()`, supply a dataset and aesthetic mapping (with `aes()`). You
then add on layers (like `geom_point()` or `geom_histogram()`), scales
(like `scale_colour_brewer()`), faceting specifications (like
`facet_wrap()`) and coordinate systems (like `coord_flip()`).

``` r
library(ggplot2)

ggplot(mpg, aes(displ, hwy, colour = class)) + 
  geom_point()
```

<img src="man/figures/README-example-1.png" alt="Scatterplot of engine displacement versus highway miles per gallon, for 234 cars coloured by 7 'types' of car. The displacement and miles per gallon are inversely correlated." width="100%" />
\## Using rminka

If you are new to ggplot2 you are better off starting with a systematic
introduction, rather than trying to learn from reading individual
documentation pages. Currently, there are three good places to start:

1.  The \[Data Visualization\]\[r4ds-vis\] and
    \[Communication\]\[r4ds-comm\] chapters in \[R for Data
    Science\]\[r4ds\]. R for Data Science is designed to give you a
    comprehensive introduction to the
    [tidyverse](https://www.tidyverse.org), and these two chapters will
    get you up to speed with the essentials of ggplot2 as quickly as
    possible.

2.  If you’d like to take an online course, try [Data Visualization in R
    With
    ggplot2](https://learning.oreilly.com/videos/data-visualization-in/9781491963661/)
    by Kara Woo.

3.  If you’d like to follow a webinar, try [Plotting Anything with
    ggplot2](https://youtu.be/h29g21z0a68) by Thomas Lin Pedersen.

4.  If you want to dive into making common graphics as quickly as
    possible, I recommend \[The R Graphics Cookbook\]\[cookbook\] by
    Winston Chang. It provides a set of recipes to solve common graphics
    problems.

If you’ve mastered the basics and want to learn more, read [ggplot2:
Elegant Graphics for Data Analysis](https://ggplot2-book.org). It
describes the theoretical underpinnings of ggplot2 and shows you how all
the pieces fit together. This book helps you understand the theory that
underpins ggplot2, and will help you create new types of graphics
specifically tailored to your needs.

## Getting help

There are two main places to get help with ggplot2:

1.  The [RStudio community](https://forum.posit.co/) is a friendly place
    to ask any questions about ggplot2.

2.  \[Stack Overflow\]\[so\] is a great source of answers to common
    ggplot2 questions. It is also a great place to get help, once you
    have created a reproducible example that illustrates your problem.

For more information go to [Minkar
website](https://development-biomarine.github.io/rminkav3/)
