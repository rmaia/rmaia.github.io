---
title: pavo
layout: singlenohead
author_profile: true
permalink: /pavo/
---

# pavo: Perceptual Analysis, Visualization and Organization of Spectral Color Data in R

## Updates (current version: 1.0.0, 12/05/2016)  

Pavo 1.0.0 is the first major update of pavo since its first release. Find out more:  

* [What's new on pavo 1.0.0](../pavo-vig-1_0.html)
* [Pavo vignette](../pavo-vig.html)

**Need help with pavo? Just click on the "open chat" button below!** The package now has a Gitter page - a public chat room where we will promptly be answering any questions and making announcements about package development. [![Join the chat at https://gitter.im/r-pavo/help](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/r-pavo/help?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

We're very pleased to welcome [Thomas White](http://tomwhite.io/) to our development team! Tom is helping us make some changes for the big update coming soon, as well as [incorporating additional visual models](https://github.com/thomased/colsci) to the package.

**citing pavo.** the manuscript describing the package is:
Maia, R., Eliason, C.M., Bitton, P.-P., Doucet, S.M. & Shawkey, M.D. 2013. pavo: an R package for the analysis, visualization and organization of spectral data. Methods in Ecology and Evolution, 4(10):906-913. [doi: 10.1111/2041-210X.12069](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12069/abstract)

[pavo on CRAN](https://cran.r-project.org/web/packages/pavo/index.html)  
[manual](https://cran.r-project.org/web/packages/pavo/pavo.pdf) for implemented functions  

<script>
  ((window.gitter = {}).chat = {}).options = {
    room: 'r-pavo/help'
  };
</script>
<script src="https://sidecar.gitter.im/dist/sidecar.v1.js" async defer></script>

## About pavo

<img align="left" style="padding-right:25px" src="/images/pavoplot.jpg">
We have developed pavo to provide a seamless workflow for color data analysis from reflectance spectra. The package provides functions for:

* importing and interpolating raw spectral data obtained using spectrometers and microspectrometers of several makes (Avantes, OceanOptics, CRAIC…)
processing (smoothen, normalize, correct, etc.) spectra and aggregating multiple measurements
* calculation of multiple trichromatic variables (hue/saturation/brightness)
several plotting options – both for exploratory analyses and for presenting results
* multiple models based on visual systems
  
This is all implemented taking advantage of object classes and general functions, which should allow for an easy transition to the package’s functions to any R user. pavo is installable directly from R like most packages by calling install.packages(“pavo”). We have extensively documented most of the package’s capabilities in the accompanying vignette.