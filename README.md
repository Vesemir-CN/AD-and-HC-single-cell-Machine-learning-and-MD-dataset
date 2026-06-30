# AD-and-HC-single-cell-Machine-learning-and-MD-dataset

Supplementary data for single-cell machine learning and molecular dynamics analysis

## Zenodo Data Repository

All data is hosted on Zenodo:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

**Note:** This repository contains only the README file. All data files are available for download from Zenodo.

## Contents on Zenodo

### GSEA Result Tables
- `GSEA result table/CA2_Hallmark.csv` - Hallmark pathway analysis for CA2
- `GSEA result table/CA2_Kegg.csv` - KEGG pathway analysis for CA2
- `GSEA result table/KCs9_Hallmark.csv` - Hallmark pathway analysis for KCs9
- `GSEA result table/KCs9_Kegg.csv` - KEGG pathway analysis for KCs9

### Molecular Dynamics (MD)
- `MD and MS/MD/` - Molecular docking results and structures
- `MD and MS/MS/MSfigure/` - MS analysis figures and statistics
- `MD and MS/MS/MSfigure/movie_noWater.pdb` - MD simulation trajectory

### Machine Learning (ML)
- `ML/combination_results.csv` - Ensemble model results
- `ML/final_consensus_genes.csv` - Consensus gene list
- `ML/gene_voting_results.csv` - Gene voting results
- `ML/shap_results.rds` - SHAP analysis results
- `ML/single_algorithm_models.rds` - Machine learning models

### Processed Data
- `processed data(rds)/CODE.R` - R code for data processing
- `processed data(rds)/scRNA.rds` - Processed scRNA-seq data
- `processed data(rds)/scRNA_M.rds` - Processed scRNA-seq metadata

## Usage

1. Download all data from Zenodo
2. Run the R code in `processed data(rds)/CODE.R` to reproduce the analysis

## Citation

If you use this data, please cite our publication and the Zenodo repository.