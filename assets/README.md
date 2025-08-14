# Assets Directory

This directory contains all datasets, processed files, and reference data used in the Precision Oncology through Interpretable Machine Learning project.

## Structure Overview

```
assets/
├── *.csv                          # Summary and analysis files
├── *.tsv                          # Tab-separated data files
├── Gencode/                       # Reference genome annotations
├── GSE161529/                     # Validation dataset 1
├── GSE176078/                     # Primary training dataset
└── GSE180286/                     # Validation dataset 2
```

## File Descriptions

### Analysis Summary Files
- **breast_cancer_gene_analysis.csv** - Comprehensive gene analysis results for breast cancer
- **Clinical_Trials_Summary.csv** - Clinical trial data for therapeutic targets
- **Combined_DE.csv** - Combined differential expression analysis across datasets
- **interactions.tsv** - Gene interaction network data
- **Oncogene_therapeutic_stratification.csv** - Oncogene-based therapeutic stratification
- **OpenTargets_Score.csv** - Open Targets platform association scores

### Dataset Directories
- **[Gencode/](Gencode/)** - Reference genome annotations (see Gencode/README.md)
- **[GSE161529/](GSE161529/)** - Validation dataset 1 (see GSE161529/README.md)
- **[GSE176078/](GSE176078/)** - Primary training dataset (see GSE176078/README.md)
- **[GSE180286/](GSE180286/)** - Validation dataset 2 (see GSE180286/README.md)

## File Formats
- **`.h5ad`** - AnnData objects containing single-cell data
- **`.csv`** - Comma-separated analysis results and metadata
- **`.tsv`** - Tab-separated count matrices and feature files
- **`.mtx`** - Matrix Market format for sparse count matrices
- **`.gtf`** - Gene Transfer Format for genome annotations

## Important Notes
- Large files are not tracked in git
- Processing requires substantial RAM (16GB+ recommended)
- Refer to individual dataset README files for specific details