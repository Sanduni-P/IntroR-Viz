<!-- badges: start -->
[![Check, build, and push image](https://github.com/PMacDaSci/R4CancerSci/actions/workflows/basic_checks.yaml/badge.svg)](https://github.com/PMacDaSci/R4CancerSci/actions/workflows/basic_checks.yaml)
<!-- badges: end -->

# Introduction

This site contains the materials for an R course run by Peter Mac.

This workshop is designed to provide beginners with foundational understanding of R programming language. Through a combination of theoretical explanations, hands-on coding exercises, and practical applications, participants will learn how to leverage R for data analysis, manipulation and visualization cancer biology datasets. 

The workshop will cover essential programming concepts and gradually introduce more advanced topics, with a focus on using the tidyverse package suite for efficient data handling, analysis and visualization. The aim of this workshop is to improve the reproducibility and efficiency of scientific research by teaching powerful tools in data analysis and creating informative plots.

# Instructor

Sandun Rajapaksa

# Learning Objectives

Participants will gain the following skills:

- Proficiency in using R and RStudio for data analysis.
- Basic R programming skills.
- Reading, tidying, and joining datasets using `readr` and `tidyr` packages. 
- Data manipulation and transformation using `dplyr` package.
- Creating various types of plots using `ggplot2` package.

# Data

The Metabric study characterized the genomic mutations and gene expression profiles for 2509 primary breast tumours. In addition to the gene expression data generated using microarrays, genome-wide copy number profiles were obtained using SNP microarrays. Targeted sequencing was performed for 2509 primary breast tumours, along with 548 matched normals, using a panel of 173 of the most frequently mutated breast cancer genes as part of the Metabric study.

**Refrences: **

- [Curtis *et al.*, Nature 486:346-52, 2012](https://pubmed.ncbi.nlm.nih.gov/22522925)
- [Pereira *et al.*, Nature Communications 7:11479, 2016](https://www.ncbi.nlm.nih.gov/pubmed/27161491)

Both the clinical data and the gene expression values were downloaded from
[cBioPortal](https://www.cbioportal.org/study/summary?id=brca_metabric).

We excluded observations for patient tumor samples lacking expression data, resulting in a data set with fewer rows.

# Into the tidyverse

The core tidyverse includes the packages that you're likely to use in
everyday data analyses. Therefore, this workshop offers an introduction
to these core packages. As of tidyverse 1.3.0, the following packages
are included in the core tidyverse:

![](vignettes/images/tidyverse-packages.png)

Hex logos for the eight core tidyverse packages and their primary
purposes. Image
source:<https://education.rstudio.com/blog/2020/07/teaching-the-tidyverse-in-2020-part-1-getting-started/>

- [**ggplot2**](https://ggplot2.tidyverse.org/): *Grammar of Graphics.* Enables the creation of graphics in a declarative manner.
- [**dplyr**](https://dplyr.tidyverse.org/): *Grammar for data manipulation*. Presents a set of verbs to address common challenges in data manipulation.
- [**tidyr**](https://tidyr.tidyverse.org/): Provides a collection of functions for achieving tidy data.
- [**readr**](https://readr.tidyverse.org/): Facilitates the rapid and user-friendly reading of rectangular data (e.g., csv, tsv, and fwf).
- [**purrr**](https://purrr.tidyverse.org/): *Functional programming toolkit.* Offers a set of tools for efficient work with functions and vectors.
- [**tibble**](https://tibble.tidyverse.org/): *Tibbles*, a modern re-imagining of the data frame, offering a more user-friendly and efficient approach to handling tabular data.
- [**stringr**](https://stringr.tidyverse.org/): Provides a set of functions designed to simplify and enhance string manipulations.
- [**forcats**](https://forcats.tidyverse.org/):  Provides a suite of useful tools for handling and manipulating categorical variables (*factors*).

# Credits and Acknowledgement

These content were adapted from the following course materials:

 - [OHI Data Science Training](http://ohi-science.org/data-science-training/index.html)
 - [Data Carpentry](https://datacarpentry.org)
 - [WEHI tidyr coursebook](https://bookdown.org/ansellbr/WEHI_tidyR_course_book/) by Brendan R. E. Ansell
 - content developed by Maria Doyle.

------------------------------------------------------------------------
