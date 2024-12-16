
# README

## Overview
This document, **Clustering and EigenFaces Project**, showcases solutions to clustering and dimensionality reduction problems using Python. It includes tasks related to k-means, agglomerative clustering, and PCA (Principal Component Analysis), utilizing datasets such as the Iris dataset and a facial image dataset.

## Contents

1. **Clustering Algorithms**:
   - **Iris Dataset**: 
     - Analysis of clustering tendencies using the first two features.
     - Implementation of k-means clustering with varying numbers of clusters (`k = 2, 5, 20`).
     - Exploration of agglomerative clustering with single and complete linkage methods for `k = 2, 5, 20`.
     - Comparison of results between k-means and agglomerative clustering.

2. **PCA and EigenFaces**:
   - Facial image dataset:
     - Mean subtraction for zero-mean data preparation.
     - Singular Value Decomposition (SVD) for dimensionality reduction.
     - Analysis of PCA-reconstructed images for various numbers of principal components (`K = 5, 10, 50, 100`).
     - Visualization of latent space using the first two principal components.

## Prerequisites

The code examples in the document require the following:
- Python 3
- Libraries:
  - `numpy`
  - `scipy`
  - `matplotlib`
  - Custom library `mltools` (referenced but not included)

## Usage

This project serves as a step-by-step guide to implementing clustering and PCA in Python. Follow the code snippets and descriptions to reproduce results or adapt them for similar datasets and tasks.

## Key Features

- **Clustering**:
  - Comparative study of clustering methods and their visualizations.
  - Insights into differences between partition-based and hierarchical methods.
  
- **Dimensionality Reduction**:
  - Practical application of PCA to understand the underlying structure of facial data.
  - Visualization of eigenfaces and latent spaces.

## Limitations

- The `mltools` package is assumed to be available and functional, but its source is not provided in the document.
- Specific datasets (`iris.txt`, `faces.txt`) are referenced but not included.

## Author

This project was authored by **Amirali Mohseni**. For questions or further discussions, please reach out to the author.
