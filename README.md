
<!-- README.md is generated from README.Rmd. Please edit that file -->

# prismaread <a href='https://github.com/lbusett/prismaread'><img src='man/figures/logo.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/lbusett/prismaread.svg?branch=master)](https://travis-ci.org/lbusett/prismaread)
[![Lifecycle:
beta](https://img.shields.io/badge/lifecycle-beta-blue.svg)](https://www.tidyverse.org/lifecycle/#beta)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4019081.svg)](https://doi.org/10.5281/zenodo.4019081)
[![codecov](https://codecov.io/gh/lbusett/prismaread/branch/master/graph/badge.svg)](https://codecov.io/gh/lbusett/prismaread)
<!-- badges: end -->

`prismaread` allows easily importing PRISMA hyperspectral data
(<http://www.prisma-i.it/index.php/it/>) from the original data provided
by ASI in HDF format, and convert them to a easier to use format (ENVI
or GeoTiff). It also provides functionality to automatically computing
Spectral Indexes from either the original HDF data or from hyperspectral
data already converted using function `pr_convert`, and for easily and
quickly extract data and compute statistics for the different bands over
areas of interest.

<a href="http://www.irea.cnr.it/en/">
<img src="man/figures/logo_irea.png" height="60" align="left" style="vertical-align:middle;margin:0px 10px"/></a>

*`prismaread` is developed and maintained by Lorenzo Busetto and Luigi
Ranghetti, [Institute of Remote Sensing of
Environment](http://www.irea.cnr.it/en/) - National Research Council -
Italy (CNR-IREA)*

# Installation

You can install the last stable version of `prismaread` from
[GitHub](https://github.com/) using:

``` r
# install.packages("remotes")
remotes::install_github("lbusett/prismaread", ref = "v1.0.0")
library(prismaread)
```

, or the last development version using:

``` r
# install.packages("remotes")
remotes::install_github("lbusett/prismaread")
library(prismaread)
```

# Usage

See `prismaread` [website](https://lbusett.github.io/prismaread/) for
further instructions and info on output formats.

# Future Work

  - Improve speed of writing FULL hyperspectral cubes

  - Clean up code

## Citation

To cite `prismaread` please use:

Busetto, L., Ranghetti, L. (2020) prismaread: A tool for facilitating
access and analysis of PRISMA L1/L2 hyperspectral imagery v1.0.0, URL:
<https://lbusett.github.io/prismaread/>, doi:
<https://doi.org/10.5281/zenodo.4019081>

## Website

For more information, documentation and examples of use, **see also the
prismaread website at <https://github.com/lbusett/prismaread/>**
