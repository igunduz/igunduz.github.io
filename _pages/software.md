---
permalink: /software/
title: "Software"
gallery:
  - url: software/deconvR_logo.png
    image_path: software/deconvR_logo.png
    alt: "R/Bioconductor Package for Simulation and Deconvolution of Omic Profiles"
    title: "R/Bioconductor Package for Simulation and Deconvolution of Omic Profiles"
---

I benefited from countless open-source materials and software until now. I'm
eager to adopt the open-source methodology as a principle and share the code
I've written to use it in my work. In addition, I value developing software for
sharing methods that can be used over and over again on easily accessible
platforms such as [Bioconductor.](https://www.bioconductor.org/)

Below you will find the R package called
[**deconvR**](https://bioconductor.org/packages/release/bioc/html/deconvR.html),
which I had the opportunity to develop during my internship at [Max Delbrück Center for Molecular Medicine](https://www.mdc-berlin.de/).

# deconvR

[![R-CMD-check-bioc](https://github.com/BIMSBbioinfo/deconvR/actions/workflows/check-bioc.yml/badge.svg)](https://github.com/BIMSBbioinfo/deconvR/actions/workflows/check-bioc.yml)
[![R-CMD-check](https://github.com/BIMSBbioinfo/deconvR/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/BIMSBbioinfo/deconvR/actions/workflows/R-CMD-check.yaml)
[![codecov](https://codecov.io/gh/BIMSBbioinfo/deconvR/branch/master/graph/badge.svg?token=F86XU6BI9S)](https://codecov.io/gh/BIMSBbioinfo/deconvR)
[![](https://img.shields.io/badge/release%20version-1.0.1-green.svg)](https://www.bioconductor.org/packages/deconvR)

<!-- badges: start -->
<!-- badges: end -->

I am a developer of the [deconvR](https://bioconductor.org/packages/release/bioc/html/deconvR.html) an R/Bioconductor package provides a collection of functions
designed for analyzing deconvolution of the bulk sample(s) using an atlas of
reference signature profiles and a user-selected model (non-negative least
squares,quadratic programming, support vector regression, or robust linear
regression). 

{% include gallery %}

## Installation

And **deconvR** package can be installed from Bioconductor:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("deconvR")
```

You can also install the development version of **deconvR** directly from
Github:

``` r
remotes::install_github("BIMSBbioinfo/deconvR")
```

## How to Use deconvR

User who wish to expand their own reference atlas can use `findSignatures`
function. `atlas` is the signature matrix to be extended and `samples` the new
data to be added to the signature matrix. `atlas` and `samples` are compliant
with the function requirements. After providing appropriate `atlas` format,
users can create `samples` using `simulateCellMix` function. You can get more
information about **deconvR** from
[here](http://bioinformatics.mdc-berlin.de/deconvR/) and also
[here.](https://bioconductor.org/packages/release/bioc/html/deconvR.html)
