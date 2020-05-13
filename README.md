
# Inference on the signal-noise ratio of the Markowitz portfolio

[![Build Status](https://travis-ci.org/shabbychef/snrinf.svg?branch=master)](https://travis-ci.org/shabbychef/snrinf)

This repo holds the code to rebuild the paper, "Inference on Achieved Signal Noise Ratio."
There are a few ways to build the paper:

1. Build it locally on your computer via `knitr` and `R`. This will require
the following packages:
`knitr`, `devtools`, `future.aplpy`, `dplyr`, `ggplot2`, `knitr`, 
`quantmod`, `SharpeR`, `tidyr`, `xtable`, 
and `aqfb.data`, which is available from github via
```r
install_github("shabbychef/aqfb_data")
```
Then you can build via
```r
knitr::knit('snrinf.Rnw')
```

