# Tree Growth and Gene Expression Analysis

This repository contains an R Markdown workflow for analyzing tree growth data and RNA-seq gene expression data.
The analysis explores differences in tree growth across control and treatment sites, as well as gene expression patterns across biological samples.

The data files used in this project were downloaded from Ghazanfar Khan’s GitHub repository.
1. gene_expression.tsv  
2. growth_data.csv

# Features
# RNA-seq Gene Expression

- Read and process RNA-seq count data.

- Compute mean expression across samples.

- Identify the top 10 most highly expressed genes.

- Generate histograms of expression values.

# Tree Growth Data

- Import and summarize circumference measurements.

- Calculate the mean and standard deviation of tree circumference at the start (2000) and end (2020) of the study.

- Create boxplots comparing tree growth at control vs. treatment sites.

- Calculate growth over the last 10 years (2010–2020).

# Repository Contents

1. gene_expression.Rmd: Gene expression summary, top expressed genes, histogram plots.

2. tree_growth.Rmd: Growth analysis, boxplots, summary tables, and t-test results.

Figures 5: Expression histograms, boxplots of growth.

Tables 6: Gene expression tables, site-wise growth summaries.

# Prerequisites

This project requires R (>= 4.0) and the following packages:

- Histograms

- knitr, rmarkdown

- stats
# Authors
Teja Sri Abburu
