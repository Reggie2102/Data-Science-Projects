# Protein Structure Dataset Analysis
## Overview

This project involves data cleaning, exploratory data analysis (EDA), and predictive modeling on a large protein dataset retrieved from the RCSB Protein Data Bank (PDB). The dataset contains structural and sequence data for over 400,000 proteins, making it valuable for bioinformatics, drug discovery, and structural biology research.

## Context
The Protein Data Bank (PDB) is a globally recognized repository of 3D structural data for large biological molecules such as proteins and nucleic acids. Structures in the PDB are determined using advanced techniques such as:

X-ray crystallography
Nuclear Magnetic Resonance (NMR) spectroscopy
Cryo-electron microscopy (cryo-EM)
This repository supports the biological and pharmaceutical research communities in understanding molecular mechanisms, disease pathways, and drug interactions.


## Dataset Description
The dataset includes two key files:

1. pdb_data_no_dups.csv
Contains meta-information about each protein, including:

structureId (unique identifier)

Protein classification

Experimental method used for structure determination

Resolution of the structure

Release date and deposition date

Macromolecule type, etc.

2. data_seq.csv
Contains over 400,000 protein structure sequences linked by structureId.

Each sequence provides insight into the amino acid composition of the proteins in the dataset.

 Source: Dataset compiled and uploaded to Kaggle from the RCSB PDB Archive

 ## Project Goals
This repository is structured to achieve the following:

Data Cleaning

Remove duplicates and missing values

Ensure alignment between metadata and sequence data

Standardize formats for further analysis

Exploratory Data Analysis (EDA)

Protein classification distributions

Experimental methods frequency

Sequence length statistics

Resolution vs. classification relationships

Predictive Modeling

Predict experimental method or classification from sequence features

Explore supervised learning models (Random Forest, XGBoost, etc.)

Feature engineering using sequence properties (e.g., amino acid frequencies)

Bioinformatics Insights

Sequence analysis using NLP-inspired techniques

Identification of potentially useful sequence motifs

## Tools & Libraries
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

Biopython (for sequence analysis)

TensorFlow / PyTorch (for deep learning models, if applicable)

## Potential Applications
Drug target identification

Protein classification automation

Structural modeling improvements

Educational use in structural biology and bioinformatics courses

## Acknowledgements
Protein structural data from the RCSB PDB

Original Kaggle dataset contribution by the community

Inspiration from the need to apply machine learning in biological sciences

## Inspiration
Understanding protein structures is essential in the life sciences. From decoding disease mechanisms to developing novel drugs, protein data plays a central role. This project is an attempt to leverage machine learning and data science techniques to uncover patterns and enable predictive modeling in this vital domain.
