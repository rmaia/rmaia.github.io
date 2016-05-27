---
title: pavo
layout: singlenohead
author_profile: true
---

# pavo: Perceptual Analysis, Visualization and Organization of Spectral Color Data in R

## Updates (current version: 0.5-5, 09/03/2016)

We're very pleased to welcome [Thomas White](http://tomwhite.io/) to our development team! Tom is helping us make some changes for the big update coming soon, as well as [incorporating additional visual models](https://github.com/thomased/colsci) to the package.

_IMPORTANT: Please update to the latest version. Note that a bug has been detected in previous versions when using the “vissyst()” function (and anything downstream) and the blue tit visual system. This bug has been fixed, but please make sure to always check the output of your results. All other input options, including other visual systems, should be working as expected. If you have any questions, please e-mail me._

**citing pavo.** the manuscript describing the package is:
Maia, R; Eliason, CM; Bitton, P-P, Doucet, SM & Shawkey, MD. pavo: an R package for the analysis, visualization and organization of spectral data. Methods in Ecology and Evolution, 4(10):906-913. [doi: 10.1111/2041-210X.12069](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12069/abstract)

[pavo on CRAN](https://cran.r-project.org/web/packages/pavo/index.html)  
[package vignette](/pdf/pavo.pdf) (temporarily removed from CRAN release)  
[manual](https://cran.r-project.org/web/packages/pavo/pavo.pdf) for implemented functions  

## About pavo

<img align="left" style="padding-right:25px" src="/images/pavoplot.jpg">
We are happy to announce that the R package pavo is now available through CRAN. We have developed pavo to provide a seamless workflow for color data analysis from reflectance spectra. The package provides functions for:

importing and interpolating raw spectral data obtained using spectrometers and microspectrometers of several makes (Avantes, OceanOptics, CRAIC…)
processing (smoothen, normalize, correct, etc.) spectra and aggregating multiple measurements
calculation of multiple trichromatic variables (hue/saturation/brightness)
several plotting options – both for exploratory analyses and for presenting results
multiple models based on visual systems, such as the segment classification (Endler 1990), photon catch and receptor noise (Osorio & Vorobyev 1998), and tetrahedral colorspace (Endler & Mielke 2005, Stoddard & Prum 2008) models
calculation of spectral sensitivities of visual systems based on peak cone sensitivities, oil droplet filtering, and ocular media transmission.
This is all implemented taking advantage of object classes and general functions, which should allow for an easy transition to the package’s functions to any R user. pavo is installable directly from R like most packages by calling install.packages(“pavo”). We have extensively documented most of the package’s capabilities in the accompanying vignette.

We hope you enjoy!

Rafael Maia, Pierre-Paul Bitton & Chad Eliason

