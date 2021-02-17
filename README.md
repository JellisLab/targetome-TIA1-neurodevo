### Introduction
Code and data to estimate TIA1 binding efficiency with parallel RIP-seq and RNA-seq experiments during stem cell based neuronal differentiation. Look up [preprint paper](https://www.biorxiv.org/content/10.1101/2021.01.26.428265v1) for details.

### Data
Counts table in the *data* folder contains quantified pA sites for genes annotated in polyA_DB 3 database [PMID: 29069441](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5753232/). This is the only table required to run the notebook.

### R notebooks
1. **estimate_TIA1_enrichment.Rmd**

   Binding efficiency is calculated from the RIP-seq and RNA-seq as ratio between TIA1 and Input counts. Genes with sufficient enrichment of TIA1 over IgG IP are selected to eliminate immunoprecipitation bias. Stats between replicates is obtained for downstream analyses.

