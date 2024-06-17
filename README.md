<!-- badges: start -->

[![Check, build, and push image](https://github.com/PMacDaSci/R4CancerSci/actions/workflows/basic_checks.yaml/badge.svg)](https://github.com/PMacDaSci/R4CancerSci/actions/workflows/basic_checks.yaml)

<!-- badges: end -->

# Introduction

This site contains the materials for an R course run by Peter Mac.

This workshop is designed to provide beginners with foundational understanding of R programming language. Through a combination of theoretical explanations, hands-on coding exercises, and practical applications, participants will learn how to leverage R for data visualization of cancer biology datasets.

The workshop will cover essential programming concepts and gradually introduce more advanced topics, with a focus on using the ggplot2 package suite for data visualization. The aim of this workshop is to analyse data and create informative plots.

# Instructor

Sandun Rajapaksa

# Learning Objectives

Participants will gain the following skills:

-   Proficiency in using R and RStudio for data analysis.
-   Basic R programming skills.
-   Reading datasets using `readr` package.
-   Creating various types of plots using `ggplot2` package.

# Data

The Metabric study characterized the genomic mutations and gene expression profiles for 2509 primary breast tumours. In addition to the gene expression data generated using microarrays, genome-wide copy number profiles were obtained using SNP microarrays. Targeted sequencing was performed for 2509 primary breast tumours, along with 548 matched normals, using a panel of 173 of the most frequently mutated breast cancer genes as part of the Metabric study.

**Refrences:**

-   [Curtis *et al.*, Nature 486:346-52, 2012](https://pubmed.ncbi.nlm.nih.gov/22522925)
-   [Pereira *et al.*, Nature Communications 7:11479, 2016](https://www.ncbi.nlm.nih.gov/pubmed/27161491)

Both the clinical data and the gene expression values were downloaded from [cBioPortal](https://www.cbioportal.org/study/summary?id=brca_metabric).

We excluded observations for patient tumor samples lacking expression data, resulting in a data set with fewer rows.

# Credits and Acknowledgement

## Credits and Acknowledgement

^*These content were adapted from the [Introduction to R: exploring the tidyverse](https://sanduni-p.github.io/IntroR/) course materials.*^

------------------------------------------------------------------------
