# Project Overview
Gene expression profiles can provide key insights to cell type, function, and health. Cells in different tissues often express vastly different genes,
allowing them to specialize in their functionality. In cancerous cells, however, gene expression is atypical for a cell of its type. In other words,
high expression of a gene in one cell type can be normal whereas it can be indicative of cancer in another cell type. These anomalies can therefore be
used to classify cells into different cancer types based on their gene expression. 

This project investigates whether machine learning models (specifically logistic regression, random forest, and XGBoost) can accurately classify cancer type using gene expression data. Using RNA-seq expression profiles paired with clinical metadata, the goal is to evaluate how well different models capture cancer-specific expression patterns and to compare their predictive performance.

The datasets used in this project were obtained from The Cancer Genome Atlas (TCGA):

**1. Gene Expression (RNA-seq) – Batch-effect–normalized mRNA expression data**
https://xenabrowser.net/datapages/?dataset=EB%2B%2BAdjustPANCAN_IlluminaHiSeq_RNASeqV2.geneExp.xena&host=https%3A%2F%2Fpancanatlas.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443

**2. Phenotype Data – Curated clinical and survival metadata**
https://xenabrowser.net/datapages/?dataset=Survival_SupplementalTable_S1_20171025_xena_sp&host=https%3A%2F%2Fpancanatlas.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443

### Acknowledgements
This project was completed as my midterm project for Professor Tala Talaei Khoei's graduate Machine Learning course at Northeastern University.
