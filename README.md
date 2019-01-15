# mlr3featsel

_mlr3featsel_ adds filters, feature selection methods and embedded feature selection methods of algorithms to _mlr3_.

[![Travis build status](https://travis-ci.org/mlr-org/mlr3featsel.svg?branch=master)](https://travis-ci.org/mlr-org/mlr3featsel)
[![CRAN status](https://www.r-pkg.org/badges/version/mlr3featsel)](https://cran.r-project.org/package=mlr3featsel)
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![Coverage status](https://codecov.io/gh/mlr-org/mlr3featsel/branch/master/graph/badge.svg)](https://codecov.io/github/mlr-org/mlr3featsel?branch=master)

## Installation

The package is currently in development and not yet usable.

## Implementation

### Implemented filters

* `stats::cor(method = "spearman")`
* `stats::cor(method = "pearson")`
* `stats::kruskal.test()`
* `stats::var()`
* `AUC` -> `mlr3measures::measureAUC`
* `FSelectorRcpp::information.gain(type = "gainratop")`
* `FSelectorRcpp::information.gain(type = "infogain")`
* `FSelectorRcpp::information.gain(type = "symuncert")`
* `praznik::CMIM()`
* `praznik::DISR()`
* `praznik::JMI()`
* `praznik::JMIM()`
* `praznik::MIM()`
* `praznik::NJMIM()`


#### Methods

* $calculate(): Calculates Filter values
* $filter(): filters the task by a given criterion

* $filter_values: Filter values
* $filtered_task: Filtered task

### Implemented wrappers

### Implemented embedded methods

test
