# GWAS
This project is a classroom project for the “BVG-7003: Analysis of genomic information: from genome to phenome” course, for GWAS analysis.
R version 4.2.0 and Rstudio version 2022.7.1.554 for windows were used to write and edit the scripts.
Two R packages are used for GWAS analysis. GAPIT3 and rMVP.
 
•	GAPIT3 could be install and load using devtools:
install.packages("devtools")
devtools::install_github("jiabowang/GAPIT3",force=TRUE)
library(GAPIT3)

•	rMVP could be install and load using CRAN:
install.packages("rMVP")
library(rMVP)

We need to import the data files that we will be using for doing the analysis which are two files:
The phenotypic (pheno.txt) and the hapmap (geno.hmp.txt) file. 
Any detail about each line of the scripts is explained by comments inside the R scripts.


