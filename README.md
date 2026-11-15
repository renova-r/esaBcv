# esaBcv

Estimates the number of latent factors of a data matrix by bi-cross-validation and then the factor matrix and noise variances, for high- or low-dimensional factor analysis.

Compatibility updates by Renova.

Version 1.2.1.1.9001 compares only the first class of `try()` results in three `if()` conditions, as current R requires a length-one condition, and corrects the package help alias to `esaBcv-package`.

## Install

Install this release from its GitHub tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/esaBcv@renova-1.2.1.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

esaBcv is by Art B. Owen and Jingshu Wang (maintainer); the original CRAN package is at <https://CRAN.R-project.org/package=esaBcv>. License: GPL (>= 2); see [COPYING](COPYING).
