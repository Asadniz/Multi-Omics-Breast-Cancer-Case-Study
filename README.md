# Multi-Omics Analysis of Breast Cancer (TCGA-BRCA)

**R-based analysis** of TCGA Breast Cancer RNA-Seq, Copy Number, and clinical data.

## Project Overview
Performed comprehensive multi-omics analysis on **1,212 TCGA-BRCA samples** (20,531 genes) to:
- Identify differentially expressed genes between tumor and normal tissue using multiple feature selection methods (BSS/WSS, Wilcoxon, Mutual Information, etc.)
- Build and compare **10+ supervised classification models** (Random Forest, XGBoost, LDA, SVM, etc.) achieving up to **98.35% accuracy**
- Apply **10 different unsupervised clustering algorithms** (PAM, Hierarchical, DBSCAN, GMM, Spectral, SOM, HDBSCAN, etc.) with PCA visualization
- Generate heatmaps and perform CNA (Copy Number Alteration) analysis

## Key Skills Demonstrated
- TCGA data processing & normalization (RSEM)
- Feature selection & dimensionality reduction (PCA)
- Supervised Machine Learning (caret, xgboost, randomForest, etc.)
- Unsupervised Learning & Clustering (cluster, dbscan, mclust, kohonen, kernlab, apcluster)
- Data visualization (ggplot2, base R, heatmaps)
- Reproducible research

## Results Highlights
- Best classification accuracy: **98.35%** (LDA, XGBoost, AdaBoost)
- Best gene ranking method for heatmap: Wilcoxon test
- PAM clustering preferred over K-means for robustness to outliers
- Clear separation of tumor vs normal samples in PCA space

## Repository Contents
- Cleaned Jupyter notebook with full analysis
- High-resolution clustering visualization plots
- Detailed answers to all 15 assignment questions

## Technologies
**R** • **Bioconductor/TCGA** • **caret** • **xgboost** • **dbscan** • **kohonen** • **PCA** • **Heatmaps**

## How to Run
```r
# Recommended: Use renv or install required packages
install.packages(c("caret", "randomForest", "xgboost", "dbscan", "mclust", "kohonen", ...))
