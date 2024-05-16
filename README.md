# Analysis of mechanisms: Modern mediation analysis for basic, clinical and epidemiological research in diabetes and endocrinology

[![License: CC BY
4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Description

This course on covers the investigation of disease mechanisms through
mediation analysis in the context of diabetes and endocrine diseases.

Our three-day course is a face-to-face workshop that includes a variety
of teaching methods, including lectures, R code-along sessions, and
activities that foster networking between participants such as group
work activities, and student presentations.

This repository contains the lesson, lecture, and assignment material
for the course, including the website source files and other associated
course administration files.

## Lesson content

The teaching material is found mainly in the project folders:

-   `preamble/`: Contains the syllabus and pre-course tasks.
-   `sessions/`: Contains the teaching material
-   `data/`: Contains the example datasets used in the course

The website is generated from [Quarto](https://quarto.org), so follows
the file and folder structure conventions from that package.

## Installing necessary packages

Packages used and depended on for this course are included in the
`DESCRIPTION` file. To install the packages, run this function in the
root directory (where the `mediation-analysis-course.Rproj` file is
located:

You might need to connect to GitHub via a personal access token if you
encounter a "rate limit" when installing packages:

``` r
# usethis::create_github_token()
gitcreds::gitcreds_set()
```

## Contributing

If you are interested in contributing to the course material, please
refer to the [contributing guidelines](CONTRIBUTING.md). Please note
that the project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md). By contributing to this project, you agree
to abide by its terms.
