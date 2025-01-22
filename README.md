
# RPG520: Course Material for Principles of Computational Oncology

<!-- badges: start -->
<!-- badges: end -->

This repository provides course material for a workshop offered as
part of Roswell Park Comprehensive Cancer Center 2025 graduate course
"Principles of Computational Oncology".

The [original content](https://mtmorgan.github.io/RPG520/) was created by Martin Morgan. 

## Installation

Workshop participants do not need to install anything. Others may
install this package using the following commands.

``` r
## install.packages("devtools")
devtools::install_github("lshep/RPG520")
```

## Content

[Day 1][] introduces the CCR 'OnDemand' compute environment, and the
basics of *R*.

[Day 2][] provides two cases studies illustrating use of *R* for data
management, visualization, and statistical analysis.

[Day 3][] illustrates additional cases studies with a computational
oncology emphasis.

[Day 4][] introduction to Bioconductor classes

The [appendix][] provides instructions on installing *R* and
*RStudio*, managing packages, and retrieving data sets used in
workshop.

[Day 1]: articles/day_1.html
[Day 2]: articles/day_2.html
[Day 3]: articles/day_3.html
[Day 4]: articles/day_4.html
[appendix]: articles/z_appendix.html

## Grading for this week

The task for this week is to write an *R* script that performs data
management and statistical analysis of a data set of your choice --
essentially reproducing selected steps in the work that we will do on
Wednesday.

You will provide me (on the CCR server) with a file 'your_name.R'. I
will run the file in a new *R* session using the command
`source('your_name.R', echo = TRUE)`. This will read and evaluate each
*R* command in the file.

Grading will be out of 10, with the following thresholds

- 7 / 10 if `source('your_name.R', echo = TRUE)` works without error.
- 8 / 10 for scripts that implement more extensive analyses, or that
  present interesting or complicated data.
- up to 10 / 10 for work that goes beyond the material we cover this
  week, e.g., using 'Rmarkdown' to present your work, performing
  additional (and appropriate) data manipulation steps using dplyr or
  other packages, additional visualizations or statstical analyses.

Note that the 7 / 10 score could be obtained by copying & pasting (a
subset of) the commands from Wednesday's lab into
'your_name.R'. Please feel free to contact or speak with me if you
have problems.

