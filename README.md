
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pkgdownreprex

<!-- badges: start -->

[![Title](https://img.shields.io/badge/pkgdown-reprex-green.svg)]() [![R
build
status](https://github.com/fmmattioni/pkgdownreprex/workflows/R-CMD-check/badge.svg)](https://github.com/fmmattioni/pkgdownreprex/actions)
<!-- badges: end -->

The goal of `pkgdownreprex` is to test different settings from the
`pkgdown` package for rendering the website. It is algo going to be used
in case a `reprex` is needed to be shared with the developers.

## Package creation workflow:

1.  `usethis::create_package()`

2.  `usethis::use_mit_license()`

3.  `gitignore::gi_fetch_templates(template_name = c("macOS", "R"),
    append_gitignore = TRUE)`

4.  `usethis::use_readme_rmd()`

5.  `usethis::use_pkgdown()`

6.  `usethis::use_vignette("pkgdownreprex")`

7.  `usethis::use_git()`

8.  `usethis::use_git_remote(name = "origin", url =
    "https://github.com/fmmattioni/pkgdownreprex.git")`

9.  `usethis::use_github_actions()`

10. `usethis::use_github_action("pkgdown")`

<details>

<summary>Session info</summary>

``` r
sessioninfo::session_info()
#> ─ Session info ───────────────────────────────────────────────────────────────
#>  setting  value                       
#>  version  R version 3.6.1 (2019-07-05)
#>  os       macOS Catalina 10.15.4      
#>  system   x86_64, darwin15.6.0        
#>  ui       X11                         
#>  language (EN)                        
#>  collate  en_US.UTF-8                 
#>  ctype    en_US.UTF-8                 
#>  tz       Europe/Berlin               
#>  date     2020-04-13                  
#> 
#> ─ Packages ───────────────────────────────────────────────────────────────────
#>  package     * version    date       lib source                         
#>  assertthat    0.2.1      2019-03-21 [1] CRAN (R 3.6.0)                 
#>  cli           2.0.2      2020-02-28 [1] CRAN (R 3.6.0)                 
#>  crayon        1.3.4      2017-09-16 [1] CRAN (R 3.6.0)                 
#>  digest        0.6.25     2020-02-23 [1] CRAN (R 3.6.0)                 
#>  evaluate      0.14       2019-05-28 [1] CRAN (R 3.6.0)                 
#>  fansi         0.4.0.9002 2020-02-28 [1] Github (brodieg/fansi@250099f) 
#>  fs            1.4.1      2020-04-04 [1] CRAN (R 3.6.1)                 
#>  glue          1.4.0.9000 2020-04-13 [1] Github (tidyverse/glue@2a47dd6)
#>  htmltools     0.4.0      2019-10-04 [1] CRAN (R 3.6.0)                 
#>  knitr         1.28       2020-02-06 [1] CRAN (R 3.6.0)                 
#>  magrittr      1.5        2014-11-22 [1] CRAN (R 3.6.0)                 
#>  MASS          7.3-51.4   2019-03-31 [1] CRAN (R 3.6.1)                 
#>  memoise       1.1.0      2017-04-21 [1] CRAN (R 3.6.0)                 
#>  pkgdown     * 1.5.1.9000 2020-04-13 [1] Github (r-lib/pkgdown@cb74ce0) 
#>  Rcpp          1.0.4.6    2020-04-09 [1] CRAN (R 3.6.1)                 
#>  rlang         0.4.5      2020-03-01 [1] CRAN (R 3.6.0)                 
#>  rmarkdown     2.1        2020-01-20 [1] CRAN (R 3.6.1)                 
#>  sessioninfo   1.1.1      2018-11-05 [1] CRAN (R 3.6.0)                 
#>  stringi       1.4.6      2020-02-17 [1] CRAN (R 3.6.1)                 
#>  stringr       1.4.0      2019-02-10 [1] CRAN (R 3.6.0)                 
#>  usethis     * 1.6.0.9000 2020-04-13 [1] Github (r-lib/usethis@3edf973) 
#>  withr         2.1.2      2018-03-15 [1] CRAN (R 3.6.0)                 
#>  xfun          0.12       2020-01-13 [1] CRAN (R 3.6.0)                 
#>  yaml          2.2.1      2020-02-01 [1] CRAN (R 3.6.1)                 
#> 
#> [1] /Library/Frameworks/R.framework/Versions/3.6/Resources/library
```

</details>
