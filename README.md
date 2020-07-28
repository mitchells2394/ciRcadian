---
title: "README"
author: "Mitchell"
date: "7/28/2020"
output: 
  html_document: 
    keep_md: yes
---

### ciRcadian
R package to expedite some circadian rhythm analysis for the Harmer lab. 

### How to Install 
Preferred way to install this package is through the devtools package: 

```r
devtools::install_github("mitchells2394/ciRcadian", 
                         upgrade = FALSE, 
                         build_vignettes = TRUE)
```

Functions in this package depend on those found in other package, specifically `ggplot2`, `dplyr`, `tidyr`, `readxl`, `readr`, and `rlang`. Therefore, the fastest way to load up this package for use after installation is through 

```r
library(tidyverse)
library(rlang)
library(ciRcadian)
```

### Overview 
The best introduction to this package is found in the package's vignette, which can be accessed after loading the package through 

```r
vignette(package = "ciRcadian", topic = "introduction")
```

Additional information about this package can be accessed through the package's description, accessed through 

```r
packageDescription(pkg = "ciRcadian")
```

or through accessing documentation such as 

```r
?ciRcadian::luc_organize()
```
