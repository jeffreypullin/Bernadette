
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Bernadette <img src="https://github.com/bernadette-eu/bernadette-eu.github.io/blob/9588dba70edb87adc5b026ec0ae1912c290bfeb0/images/abc.png" align="right" height="150px" width="150px"/>

<!-- badges: start -->

[![R-CMD-check](https://github.com/bernadette-eu/Bernadette/workflows/R-CMD-check/badge.svg)](https://github.com/bernadette-eu/Bernadette/actions)
<!-- badges: end -->

## Overview

The **Bernadette** (“Bayesian inference and model selection for
stochastic epidemics”) R package provides a framework for Bayesian
analysis of infectious disease transmission dynamics via diffusion
driven multi-type epidemic models with time-varying coefficients, with a
particular focus on Coronavirus Disease 2019 (COVID-19). It allows for
evaluation of probabilistic forecasts with proper scoring rules, for the
purpose of model comparison.

## Website

The website for the BERNADETTE Marie Sklodowska-Curie Action (MSCA) is
available at: <https://bernadette-eu.github.io/>

## Installation

You can install the latest development version of **Bernadette**
(requires the [devtools](https://github.com/r-lib/devtools) package)
from [GitHub](https://github.com/) with:

``` r
if (!require("devtools")) {
  install.packages("devtools")
}
devtools::install_github("bernadette-eu/Bernadette", dependencies = TRUE, build_vignettes = FALSE)
library("Bernadette")
```

## License

This R package is provided for use under the GPL-3.0 License by the
author.
