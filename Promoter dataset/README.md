 Promoter Region Prediction Dataset
## About the Dataset
Promoters are essential DNA sequences located near the transcription start sites (TSS) of genes. They control transcription initiation by guiding the RNA polymerase to bind and begin gene expression. Accurately identifying these promoter regions is a key task in computational biology and genome annotation.

This dataset is designed for supervised machine learning models to distinguish between promoter and non-promoter sequences. The goal is to build a binary classifier that can predict whether a given DNA sequence functions as a promoter.

## Dataset Structure
The dataset includes two CSV files:

File Name	Description
promoter_sequences.csv	Contains DNA sequences that are promoter regions (labeled as positive samples)
non_promoter_sequences.csv	Contains DNA sequences that are not promoter regions (labeled as negative samples)

Each file contains at least:

ID: Unique identifier

Sequence: Raw DNA sequence (e.g., 200–1000 base pairs)

You can preprocess and merge both files into a single dataset for training purposes, adding a binary label:

1 = Promoter

0 = Non-promoter

## Objective
The main goal is to build a binary classification model that can:

Distinguish promoter vs. non-promoter sequences

Use biological features such as CpG islands, structural, and content-based characteristics

### Feature Domains
1. CpG Islands
Regions rich in CG dinucleotides

Indicative of transcriptional activity

Often found in promoter regions

2. Structural Features
Helical parameters (twist, roll, tilt)

Thermodynamic stability

Curvature and bendability

3. Content Features
Nucleotide composition (GC%, AT%, k-mers)

Motif presence (e.g., TATA box)

Positional nucleotide frequency
