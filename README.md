
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

[![R-CMD-check](https://github.com/betsymccoach/libminer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/betsymccoach/libminer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("betsymccoach/libminer")
```

## Example

This is a basic example which shows you how to solve a common problem:

To get a count of installed packages in each of your libraries,
optionally with the total sizes, use `lib_summary()`.

``` r
library(libminer)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.
