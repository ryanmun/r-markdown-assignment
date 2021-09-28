
Installation of the make command
================================
This file contains instructions describing the installation process of the software required to run Markdown files and to make the ***make*** command execute successfully .

## Quick jump to required step:
- [Installation of the make command](#installation-of-the-make-command)
  - [Quick jump to required step:](#quick-jump-to-required-step)
- [Packages required:](#packages-required)
- [Steps](#steps)
  - [installing conda forge](#installing-conda-forge)
  - [installing Git:](#installing-git)
  - [installing pandoc:](#installing-pandoc)
  - [installing make:](#installing-make)
  - [installing reticulate:](#installing-reticulate)
  - [installing rmarkdown:](#installing-rmarkdown)
  - [clone the repository :](#clone-the-repository-)
  - [installing r-base:](#installing-r-base)
  - [installing wordcloud:](#installing-wordcloud)
  - [excuting the make command:](#excuting-the-make-command)
  - [Author: Ryan Munaki](#author-ryan-munaki)
  - [Neptune code: VE16U5](#neptune-code-ve16u5)



# Packages required:

* [Git](https://git-scm.com/)
* [make](https://www.gnu.org/software/make/)
* [Pandoc](https://pandoc.org/)
* [conda-forge](https://conda-forge.org/)
* [R](https://cran.r-project.org/)
* R packages:
    * [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/)
    * [reticulate](https://cran.r-project.org/web/packages/reticulate/)
   
# Steps

 create a new eniv

        * conda create --name  webtech curl=7.78.0 httpie=2.1.0
        * conda activate webtech

## installing conda forge

        * conda config --add channels conda-forge
        * conda config --set channel_priority strict

## installing Git:
        * conda install git

## installing pandoc:
        * conda install pandoc

## installing make:
        * conda install make

## installing reticulate:
        * conda install r-reticulate

## installing rmarkdown:
        * conda install r-rmarkdown

Or

        * R
        * install.packages("rmarkdown")
        * click on the first option

## clone the repository :
        * git clone  https://github.com/jeszy75/rmarkdown-examples

## installing r-base:
        * conda install r-base
       

## installing wordcloud:
        * conda install wordcloud

## excuting the make command:
        * cd rmarkdown-examples/html_document/python/
        * make



Author: Ryan Munaki 
-------------------------
Neptune code: VE16U5
--------------------