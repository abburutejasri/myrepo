# Comparative Genomics of E. coli K-12 MG1655 and Campylobacter coli
This repository contains an R Markdown workflow for comparative genomics analysis between Escherichia coli K-12 MG1655 and Campylobacter coli (GCA_003780985).
The analysis explores differences in coding sequence metrics, base composition, codon usage bias, amino acid frequencies, and k-mer distributions.
The reference genome sequences used in this analysis were obtained from Ghazanfar Khan.

# The analysis explores:

- Coding sequence metrics

- Base composition

- Codon usage bias (RSCU)

- Amino acid frequencies

- Protein k-mer distributions (k=3–5)

# Features

1. CDS Analysis: Counts, coding capacity, length distributions

2. Base Composition: Genome-wide nucleotide frequencies (A, T, G, C)

3. Codon Usage and RSCU: Synonymous codon bias and preferences

4. Amino Acid Frequencies: Distribution across all proteins

5. K-mer Analysis: Over-/under-represented motifs

Comparative Figures and Tables: Boxplots, barplots, codon usage tables

# Repository Contents

1. cds_features.Rmd: CDS counts, lengths, coding DNA

2. base_composition.Rmd: Nucleotide frequencies and plots

3. codon_usage.Rmd: Codon bias, RSCU analysis

4. amino_acids.Rmd: Amino acid counts and plots

5. kmer_analysis.Rmd: Protein motif distributions and comparative plots

Figures: Boxplots, barplots, codon usage, k-mer comparisons

Tables: CDS counts, coding DNA, codon usage differences

# Prerequisites

Requires R (>= 4.1) and packages:
- seqinr
- knitr, rmarkdown
- box plot
- stats, graphs
 #  Authors
 Teja Sri Abburu
