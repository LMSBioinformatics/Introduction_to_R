# Introduction to R

This repository houses the 5-session `Introduction to R` course run at the MRC LMS. 

This course introduces `R` and `RStudio` and walks through the fundamentals of 
programming and data science.

Sessions 1 and 2 cover usage of the `R` programming language and how to import/export 
and manipulate data. Session 3 covers the world of `R` packages and walks through 
a practical analysis example to reinforce the first two sessions. Session 4 covers 
graphing using the `ggplot2` library and discusses visual theory and how to effectively
use colour. Session 5 finishes the course by introducing the concepts of 'tidy' 
data and the programs of the `tidyverse`.

## Getting started

Download this GitHub repository (green `Code` button > Download ZIP) and unzip 
the archive in a convenient location. All course materials and homework assignments
can be found within the `content` directory.

Note that as well as the R markdown (`*.Rmd`) documents, the practical sessions 
are rendered as slides (within the `slides` directory) and as long-format HTML documents 
(`html` directory) for you to follow along.

### Prerequisites

Before you can follow along with this course, you will need to install:

- [`R`](https://cran.r-project.org/)

- [`RStudio`](https://posit.co/download/rstudio-desktop/)

Users on Apple computers will then benefit from also installing the following:

- `Xcode`. Open a Terminal window (`⌘+Space` and type “Terminal”), copy in this 
command and press Enter ... `sudo xcode-select --install` ... which will prompt 
you for your password. For security, typing at this prompt won’t display anything,
but enter your password as normal and press `Enter`. This install will take around
10 mins.

- [`gfortran`](https://mac.r-project.org/tools/gfortran-12.2-universal.pkg)

- [`XQuartz`](https://www.xquartz.org/)
