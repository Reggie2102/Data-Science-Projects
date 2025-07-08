# Gene Expression – Bioinformatics Dataset 


## Overview
This project uses the Gene Expression – Bioinformatics Dataset (~181 KB CSV) from Kaggle, curated by Samira Shemirani. The data is ideal for exploring co-expression patterns, clustering genes, and applying machine learning models in a bioinformatics setting 

## Dataset Description
Source: Kaggle – "Gene Expression – Bioinformatics Dataset" by Samira Shemirani

Content: Gene expression measurements across samples (e.g., gene names + numerical expression data) ready for clustering and predictive analysis

## Project Objectives
Data Cleaning

Handle missing or inconsistent values

Normalize expression levels (e.g., log scaling, Min–Max)

Detect and correct encoding issues

Exploratory Data Analysis (EDA)

Univariate statistics: mean, variance, distribution of expression values

Heatmaps and correlation matrices of gene clusters

PCA to visualize sample separation

Unsupervised Learning

Clustering (e.g., K‑Means, Hierarchical)

Compare cluster quality: silhouette scores, dendrograms

If labels available (e.g., treatment vs control), train classifiers (Random Forest, SVM)

Evaluate performance (accuracy, ROC-AUC, etc.)

Interpretation

Identify and analyze clusters of co-expressed genes

Perform feature importance via models or clustering metrics

Dashboard

Build an interactive dashboard (Streamlit or Plotly Dash)

Visualize clustering results and allow dynamic gene/samples filter

