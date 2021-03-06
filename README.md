
<!-- README.md is generated from README.Rmd. Please edit that file -->
ozroaddeaths [![Travis-CI Build Status](https://travis-ci.org/ropenscilabs/ozroaddeaths.svg?branch=master)](https://travis-ci.org/ropenscilabs/ozroaddeaths) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/ropenscilabs/ozroaddeaths?branch=master&svg=true)](https://ci.appveyor.com/project/ropenscilabs/ozroaddeaths)
=======================================================================================================================================================================================================================================================================================================================================================

ozroaddeaths is a package that pulls data from the Australian Road Deaths Database, run by the Bureau of Infrastructure, Transport and Regional Economics (BITRE). This provides basic details of road transport crash fatalities in Australia as reported by the police each month to the State and Territory road safety authorities. The details provided in the database fall into two groups: 1) the circumstances of the crash, for example, date, location, crash type some details regarding the persons killed, for example, age, gender and road user group.

Installation
------------

You can install ozroaddeaths from github with:

``` r
# install.packages("devtools")
devtools::install_github("ropenscilabs/ozroaddeaths")
```

Example
-------

This is a basic example which shows you how to solve a common problem:

``` r
library(ozroaddeaths)
oz_road_fatal_crash <- oz_road_fatal_crash()
oz_road_fatal_fatalities <- oz_road_fatalities()
```
