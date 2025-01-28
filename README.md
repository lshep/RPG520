
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


Grading will be out of 40, with the following thresholds:

- 0-5/40 Submit a 'your_name_.R' script that includes some code.
- 5-10/40 If `source('your_name.R', echo = TRUE)` works without error.
- 10-20/40 If your script has a data load/read, manipulation/analysis, and
  plotting. Include comments before code chunks to explain what is being perform
  (and why).
- 20-25/40 For scripts that implement more extensive analyses, or that present interesting or complicated data.
- 25-30/40 For scripts that extend out to include additional (and appropriate)
  data mannipulations, steps using dplyr or other packages, additional visualizations or statstical analyses.
- 30-40/40 If you use 'Rmarkdown' instead of .R script. The text documentation
  should describe the code performed and why. Code should still be executed and
  run without error.
 
In all cases please included a commented section of your `sessionInfo`. Note: if
this is executed as a code chunk it will use whatever the sessionInfo is when
run at compile time. Hence, include your sessionInfo you used when
running/testing the script as a commented region and an executable code chunk. 2
point deduction that does not include a sessionInfo.

Note that a 10-20 could be obtained by copying & pasting (a subset of) the
commands from Wednesday's lab into 'your_name.R'.

Please feel free to contact or speak with me if you have problems. 
