---
title: "Thesis Analysis"
author: "Melissa Tobin"
date: '2018-09-17'
output:
      html_document:
        keep_md: true
---




```r
library(tidyverse)
```

```
## ── Attaching packages ─────────────────────────────────────────────────────────────────────────────────── tidyverse 1.2.1 ──
```

```
## ✔ ggplot2 3.0.0     ✔ purrr   0.2.5
## ✔ tibble  1.4.2     ✔ dplyr   0.7.6
## ✔ tidyr   0.8.1     ✔ stringr 1.3.1
## ✔ readr   1.1.1     ✔ forcats 0.3.0
```

```
## ── Conflicts ────────────────────────────────────────────────────────────────────────────────────── tidyverse_conflicts() ──
## ✖ dplyr::filter() masks stats::filter()
## ✖ dplyr::lag()    masks stats::lag()
```

## Reading in data


```r
gps_data <- read_csv("/Volumes/hkr-storage/Research/dfuller/Walkabilly/people/Melissa Tobin/Thesis/coordinates.csv")
```

```
## Parsed with column specification:
## cols(
##   uuid = col_character(),
##   id = col_integer(),
##   latitude = col_double(),
##   longitude = col_double(),
##   altitude = col_double(),
##   speed = col_double(),
##   direction = col_character(),
##   h_accuracy = col_double(),
##   v_accuracy = col_double(),
##   acceleration_x = col_integer(),
##   acceleration_y = col_integer(),
##   acceleration_z = col_integer(),
##   mode_detected = col_character(),
##   timestamp = col_character()
## )
```

## Including Plots

You can also embed plots, for example:

![](thesis_analysis_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
