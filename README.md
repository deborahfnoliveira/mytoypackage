
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mytoypackage

<!-- badges: start -->
<!-- badges: end -->

The goal of mytoypackage is to make it easier to split a character
vector.

## Installation

You can install the development version of mytoypackage from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("deborahfnoliveira/mytoypackage")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(mytoypackage)
x <- "alfa,bravo,charlie,delta"
str_split_one(x, pattern = ",")
#> [1] "alfa"    "bravo"   "charlie" "delta"
```
