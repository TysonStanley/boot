
<!-- README.md is generated from README.Rmd. Please edit that file -->

# boot

This is a minor adjustment from the regular `boot` package by Brian
Ripley (originally written by Angelo Canty for S). This version can take
an array of n-dimensions and bootstrap over any of those dimensions.
That is, you can bootstrap over the rows (the default), the columns
(unlikely to be necessary), or another higher dimension of an array. For
example, a 3D array where the rows and columns are measures within a
person and then bootstrap across the individuals (the third dimension of
the array). Beyond this additional functionality, the `boot` package is
identical to that found on CRAN.

## Installation

You can install the released version of boot (without this new
functionality) from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("boot")
```

You can install this version of `boot` with the functionality mentioned
above with:

``` r
remotes::install_github("tysonstanley/boot")
```
