# ML-Classification-of-Cancer-Types-Using-Gene-Expression-Data
This project implements an end-to-end machine learning pipeline to classify different cancer types based on RNA-Seq gene expression profiles.
The goal is to demonstrate the application of statistical learning methods to high-dimensional genomic data, with particular emphasis on model interpretability and biological relevance.

The project uses a real-world, publicly available dataset derived from The Cancer Genome Atlas (TCGA).

Perform exploratory data analysis on high-dimensional gene expression data
Apply dimensionality reduction techniques (PCA)
Train and evaluate supervised machine learning models
Identify biologically relevant genes driving classification
Build a clean, reproducible, and well-documented analysis pipeline

# Dataset
Source:
UCI Machine Learning Repository – RNA-Seq Gene Expression Cancer Dataset
Samples: ~800
Features: ~20,000 genes
Labels: 5 cancer types
Data type: normalized RNA-Seq gene expression
Format: CSV

This dataset is a curated subset of TCGA data.

#Technologies & Libraries
Python 3
pandas
numpy
scikit-learn
matplotlib
seaborn
Jupyter Notebook

# Methodology
1. Data Preprocessing
Removal of non-feature columns
Train-test split with stratification
Feature scaling using StandardScaler

2. Exploratory Analysis
Class distribution analysis
Principal Component Analysis (PCA) for dimensionality reduction and visualization

3. Machine Learning Models
Logistic Regression (baseline)
Random Forest Classifier

4. Model Evaluation
Accuracy, Precision, Recall, F1-score
Confusion Matrix
Comparison between models

5. Model Interpretability
Feature importance analysis from Random Forest
Identification of top predictive genes
Biological validation through literature references
