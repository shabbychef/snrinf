
# Inference on the signal-noise ratio of the Markowitz portfolio

[![Build Status](https://travis-ci.org/shabbychef/snrinf.svg?branch=master)](https://travis-ci.org/shabbychef/snrinf)

This repo holds the code to rebuild the paper, ["Inference on Achieved Signal Noise Ratio."](https://arxiv.org/abs/2005.06171)

You can build the paper yourself locally on your computer via `knitr` and `R`. This will require
the following packages:
`knitr`, `remotes`, `future.apply`, `dplyr`, `ggplot2`, `viridis`, `knitr`, `SharpeR`, `tidyr`, `xtable`, `future.apply`,
and `tsrsa`, which is available from github via
```r
remotes::install_github("shabbychef/tsrsa/rpkg")
```
Then you can build via
```r
knitr::knit('snrinf.Rnw')
```

