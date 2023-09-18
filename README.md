
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

[![R-CMD-check](https://github.com/darbycamp/libminer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/darbycamp/libminer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.
It is a toy package.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("darbycamp/libminer")
```

## Example

To get a count of installed packages in each of your libraries,
optionally with the total sizes, use `lib_summary()`.

``` r
library(libminer)

lib_summary()
#>                                                                 library
#> 1                                    C:/Program Files/R/R-4.3.1/library
#> 2                        C:/Users/Darby/AppData/Local/R/win-library/4.3
#> 3 C:/Users/Darby/AppData/Local/Temp/Rtmp8EfBL3/temp_libpath2f2c7b6a5c2a
#>   n_packages
#> 1         30
#> 2         97
#> 3          1

# specify sizes = TRUE
lib_summary(sizes = TRUE)
#>                                                                 library
#> 1                                    C:/Program Files/R/R-4.3.1/library
#> 2                        C:/Users/Darby/AppData/Local/R/win-library/4.3
#> 3 C:/Users/Darby/AppData/Local/Temp/Rtmp8EfBL3/temp_libpath2f2c7b6a5c2a
#>   n_packages  lib_size
#> 1         30  68858812
#> 2         97 163364538
#> 3          1     13315
```
