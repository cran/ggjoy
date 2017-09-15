
<!-- README.md is generated from README.Rmd. Please edit that file -->
ggjoy
=====

[![Build Status](https://travis-ci.org/clauswilke/ggjoy.svg?branch=master)](https://travis-ci.org/clauswilke/ggjoy) [![Coverage Status](https://img.shields.io/codecov/c/github/clauswilke/ggjoy/master.svg)](https://codecov.io/github/clauswilke/ggjoy?branch=master) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/ggjoy)](https://CRAN.R-project.org/package=ggjoy) [![CRAN\_Downloads\_Badge](http://cranlogs.r-pkg.org/badges/grand-total/ggjoy?color=brightgreen)](http://cranlogs.r-pkg.org/downloads/total/last-month/ggjoy)

The ggjoy package has been deprecated. Please switch over to [ggridges](https://CRAN.R-project.org/package=ggridges). To port from ggjoy to ggridges, make the following substitutions in your code:

| ggjoy function      | ggridges function              |
|:--------------------|:-------------------------------|
| `geom_joy`          | `geom_density_ridges`          |
| `geom_joy2`         | `geom_density_ridges2`         |
| `geom_joy_gradient` | `geom_density_ridges_gradient` |
| `stat_joy`          | `stat_density_ridges`          |
| `theme_joy`         | `theme_ridges`                 |

All other ggjoy functions (e.g., `geom_ridgeline`) exist under the same name in the ggridges package.
