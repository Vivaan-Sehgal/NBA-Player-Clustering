# NBA Player Clustering with Machine Learning

This repository contains the code and figures for the article:

**[Identifying NBA Player Similarity with Machine Learning (PCA, K-Means, Agglomerative Clustering)](https://medium.com/@vivaansehgal01/identifying-nba-player-similarity-with-machine-learning-pca-k-means-agglomerative-clustering-f96f598ba307)**

The goal of this project is to move beyond traditional NBA positions and identify **data-driven player archetypes** using unsupervised learning on 2024–2025 NBA statistics.

---

## Overview

- **Data:** 2024–2025 NBA season ([Basketball-Reference](https://www.basketball-reference.com/))
- **Language:** Python
- **Methods:**
  - Feature selection & normalization
  - Principal Component Analysis (PCA)
  - K-Means clustering
  - Agglomerative hierarchical clustering

All statistics are **per 100 possessions**.

---

## To start

1. Begin by downloading 2025 data final.csv.

2. Then, run NBA Player Clustering.ipynb  
  
## Repository Structure

```text
├── datasets/                     # Raw datasets
├── figures/                      # Plots and visualizations
├── 2025 data final.csv           # Finalized dataset
├── NBA Player Clustering.ipynb   # Notebook to run
└── README.md
