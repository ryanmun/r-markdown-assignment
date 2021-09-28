r-markdown-assignment
=======================

---
title: "Installation of the make command"
author: Ryan Munaki
neptune code: VE16U5
date due: September 28, 2021
output:
  r-markdown-assignment:
    widescreen: true
    smaller: true
    incremental: true
    df_print: kable
lang: en-US
---

Installing the make command
===========================

# Packages required:

* [Git](https://git-scm.com/)
* [make](https://www.gnu.org/software/make/)
* [Pandoc](https://pandoc.org/)
* [conda-forge](https://conda-forge.org/)
* [R](https://cran.r-project.org/)
* R packages:
    * [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/)
    * [reticulate](https://cran.r-project.org/web/packages/reticulate/)
   


## installing conda forge

        * conda config --add channels conda-forge
        * conda config --set channel_priority strict

## installing Git:
        * conda install git

## installing pandoc:
        * conda install pandoc

## installing reticulate:
        * conda install r-reticulate

## installing rmarkdown:
        * conda install r-rmarkdown


To build the examples execute `make` in each of the subdirectories.
