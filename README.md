# AD-and-HC-single-cell-Machine-learning-and-MD-dataset

Supplementary data for single-cell machine learning and molecular dynamics analysis

## Download Data

All supplementary data is available for download via Baidu Netdisk:

**Supplementary Data**
- Link: [https://pan.baidu.com/s/1kxPEeTUYMwRu_s9-WfJkiA](https://pan.baidu.com/s/1kxPEeTUYMwRu_s9-WfJkiA)
- Extraction code: x2r6

## Contents

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

1. Download all data from Baidu Netdisk
2. Run the R code in `processed data(rds)/CODE.R` to reproduce the analysis

## Citation

If you use this data, please cite our publication.