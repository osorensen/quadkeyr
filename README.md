
<!-- README.md is generated from README.Rmd. Please edit that file -->

# quadkeyr <img src="man/figures/logo.png" align="right" height="250" />

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental) [![R-CMD-check](https://github.com/Fernandez-Lab-WSU/quadkeyr/actions/workflows/check-standard.yaml/badge.svg)](https://github.com/Fernandez-Lab-WSU/quadkeyr/actions/workflows/check-standard.yaml) [![test-coverage](https://github.com/Fernandez-Lab-WSU/quadkeyr/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/Fernandez-Lab-WSU/quadkeyr/actions/workflows/test-coverage.yaml) [![codecov](https://codecov.io/gh/Fernandez-Lab-WSU/quadkeyr/main/graph/badge.svg)](https://codecov.io/gh/Fernandez-Lab-WSU/quadkeyr)

<!-- badges: end -->

The `quadkeyr` R package presents a comprehensive toolkit tailored for
generating raster images from QuadKeys within [Microsoft’s Bing Maps
Tile
System](https://learn.microsoft.com/en-us/bingmaps/articles/bing-maps-tile-system).
Designed to integrate Bing Maps data into R workflows, this package
facilitates the creation of QuadKey grids and rasters and introduces
specialized functions for the processing of [Facebook Mobility
data](https://dataforgood.facebook.com/).

------------------------------------------------------------------------

The goal of `quadkeyr` is to:

1.  [**Bing Maps Tile System
    functions**](https://fernandez-lab-wsu.github.io/quadkeyr/articles/quadkey_conversion.html)
    Provide functions in R to convert QuadKeys to coordinates and vice
    versa, as described in the [official
    documentation](https://learn.microsoft.com/en-us/bingmaps/articles/bing-maps-tile-system)

2.  [**Create rasters based on
    QuadKeys**](https://fernandez-lab-wsu.github.io/quadkeyr/articles/get_grid_from_quadkeys.html)
    Complete a grid of QuadKeys within a specified area and level of
    detail, and create a raster from them.

3.  [**Generate rasters from Facebook mobility
    data**](https://fernandez-lab-wsu.github.io/quadkeyr/articles/create_rasters_from_grid.html)
    Adapt the functions described in points 1 and 2 to effectively
    process and analyze Facebook mobility data.

4.  Introduce a QuadKey map application enabling users to validate
    function outcomes and offering tools for visualizing the generated
    data.

## Installation

You can install the development version of `quadkeyr` from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Fernandez-Lab-WSU/quadkeyr")
```

### References

- [Bing Maps Tile Systems -
  Microsoft](https://learn.microsoft.com/en-us/bingmaps/articles/bing-maps-tile-system)
- [`slippymath`: Slippy Map Tile
  Tools](https://cran.r-project.org/web/packages/slippymath/index.html)
