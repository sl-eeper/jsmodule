jsmodule
================

[![Build Status](https://travis-ci.org/jinseob2kim/jsmodule.svg?branch=master)](https://travis-ci.org/jinseob2kim/jsmodule) [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/jinseob2kim/jsmodule?branch=master&svg=true)](https://ci.appveyor.com/project/jinseob2kim/jsmodule) [![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/jsmodule)](https://cran.r-project.org/package=jsmodule) [![codecov](https://codecov.io/github/jinseob2kim/jsmodule/branch/master/graphs/badge.svg)](https://codecov.io/github/jinseob2kim/jsmodule) [![GitHub issues](https://img.shields.io/github/issues/jinseob2kim/jsmodule.svg)](https://github.com/jinseob2kim/jsmodule/issues) [![GitHub stars](https://img.shields.io/github/stars/jinseob2kim/jsmodule.svg)](https://github.com/jinseob2kim/jsmodule/stargazers) [![GitHub license](https://img.shields.io/github/license/jinseob2kim/jsmodule.svg)](https://github.com/jinseob2kim/jsmodule/blob/master/LICENSE)

RStudio Addins and Shiny Modules for Medical Research

Install
-------

``` r
remotes::install_github('jinseob2kim/jsmodule')
```

RStudio Addins
--------------

### Basic statistics

``` r
jsBasicGadget(mtcars)
```

![](vignettes/figures/addin.gif)

### Propensity score analysis

``` r
jsPropensityGadget(mtcars)
```

![](vignettes/figures/ps.png)

### Repeated measure analysis

``` r
jsRepeatedGadget(mtcars)
```

### Survey data analysis

``` r
library(survey)
data(api)
jsRepeatedGadget(apistrat)
```

Web applications
----------------

### Basic statistics

<http://app.anpanman.co.kr/basic>

![](vignettes/figures/basic.gif)

### Propensity score analysis

<http://app.anpanman.co.kr/ps>

### Repeated measure analysis

<http://app.anpanman.co.kr/repeated>

![](vignettes/figures/repeated.png)

### Survey data analysis

<http://app.anpanman.co.kr/survey>

![](vignettes/figures/survey.png)
