# MSCS-634_K-Means_K-MedoidsClustering_Analysis
Clustering Analysis Using K-Means and K-Medoids Algorithms

# Wine Dataset Clustering Analysis with K-Means and K-Medoids

This repository contains a Jupyter notebook that performs clustering analysis on the Wine dataset using both K-Means and K-Medoids algorithms.

## Overview

The notebook compares the performance of K-Means and K-Medoids clustering algorithms on the Wine dataset from scikit-learn. The analysis includes:

- Data loading and exploration
- Feature standardization
- Implementation of K-Means clustering
- Implementation of K-Medoids clustering
- Evaluation of clustering performance using Silhouette Score and Adjusted Rand Index
- Visualization of clusters using PCA dimension reduction

## Requirements

The following libraries are required:
- pandas
- numpy
- matplotlib
- scikit-learn
- scikit-learn-extra (for KMedoids implementation)

You can install the required packages with:
```bash
pip install pandas numpy matplotlib scikit-learn scikit-learn-extra
```

## Key Findings

- The K-Means algorithm achieves a Silhouette Score of approximately 0.28 and an Adjusted Rand Index of 0.89 on the Wine dataset
- K-Means tends to form more spherical clusters
- K-Medoids is more robust to outliers and can adapt to more arbitrary cluster shapes
- Visual comparison of both algorithms using PCA projection demonstrates their differences in cluster formation

## Dataset

The Wine dataset consists of 178 samples with 13 features derived from chemical analysis of wines from three different cultivars. The clustering algorithms attempt to recover these three natural classes.

## Visualization

The notebook includes visualizations of:
- Original data distribution
- K-Means vs. true class labels
- K-Medoids vs. true class labels
- Comparison of K-Means centroids vs. K-Medoids medoids in PCA space
