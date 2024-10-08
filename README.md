# Single-cell RNA Data Integration using Seurat and Harmony

This project focuses on integrating single-cell RNA sequencing data using the Seurat and Harmony packages in R. Single-cell RNA sequencing allows for the exploration of cellular heterogeneity, and data integration is crucial for combining datasets from different experiments or conditions. Seurat is a popular R package for single-cell data analysis, and Harmony is used for batch correction and data integration. This project demonstrates how to effectively integrate multiple datasets to achieve a unified analysis.

## Installation

To get started with this project, you need to have R and RStudio installed on your system. Follow these steps to set up the environment:

1. **Install R**: Download and install R from [CRAN](https://cran.r-project.org/).
2. **Install RStudio**: Download and install RStudio from [RStudio's website](https://www.rstudio.com/products/rstudio/download/).

Once R and RStudio are installed, you can install the required packages by running the following commands in your R console:

## Install Seurat
install.packages("Seurat")

## Install Harmony
devtools::install_github("immunogenomics/harmony", build_vignettes=TRUE)

## Datasets Used
The following datasets were used for integration:
1) Human oral mucosa cell atlas reveals a stromal-neutrophil axis regulating tissue immunity- GSE164241
2) scRNA seq of the oral squamous cell carcinoma gingivo-buccal (OSCC-GB) - GSE215403
