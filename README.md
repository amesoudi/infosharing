# From information free-riding to information sharing: how have humans solved the cooperative dilemma at the heart of cumulative cultural evolution?

This repository contains documents, code and files for the paper "From information free-riding to information sharing: how have humans solved the cooperative dilemma at the heart of cumulative cultural evolution?"

The latest version of the [paper preprint can be found on SocArXiv](https://osf.io/preprints/socarxiv/a9zty).

The file **CES_models.Rmd** is an R Markdown document used to create the preprint pdf. It also contains all of the R code required to make all of the models reported in the paper. 

The file **CES_models_SI.Rmd** is an R Markdown document used to create the Supplementary Information in the pdf. It contains all R code required to make the figures. You will need to run the code in the main CES_models.Rmd file first.

The files **info_sharing.bib** and **philosophical-transactions-of-the-royal-society-b.csl** are needed to generate the reference list.

The folder **figures** contains all figures for the paper.

## Instructions for use

Use RStudio's `Knit to PDF` option in either Rmd file to create the preprint pdfs. The parameter `eval_chunks` controls whether code is run or not. It is currently set to `FALSE` at the top of each file; this means that models are not actually run and figures are not created, just loaded from the figures folder. Change it to `TRUE` to generate the figures from scratch (NB this will take a while, so you might want to run each chunk and create each figure sequentially instead).

This work was supported by the [Cultural Evolution Society Transformation Fund](https://ces-transformationfund.org/our-projects/cooperation-and-cumulative-culture/), underwritten by the John Templeton Foundation, Grant #61913. The opinions expressed in this publication are those of the authors and do not necessarily reflect the views of the John Templeton Foundation.
