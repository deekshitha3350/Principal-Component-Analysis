# Principal-Component-Analysis
# PCA and Clustering Analysis on Wine Dataset

This repository contains an analysis of the "Wine" dataset using Principal Component Analysis (PCA) and K-Means clustering. The main objective is to evaluate how dimensionality reduction through PCA impacts clustering performance and visualization.

## Project Overview

This project focuses on the following tasks:

1. **Exploratory Data Analysis (EDA):**
   - Load the wine dataset and perform basic data exploration (e.g., checking for missing values, descriptive statistics).
   - Visualize feature distributions using histograms, boxplots, and a heatmap to understand the correlations between variables.

2. **Dimensionality Reduction with PCA:**
   - Standardize the data to have a mean of 0 and a standard deviation of 1.
   - Apply PCA to reduce the dimensionality of the dataset and visualize the explained variance ratio.

3. **Clustering on Original Data:**
   - Perform K-Means clustering on the original dataset.
   - Visualize the results of clustering using scatter plots and evaluate clustering performance using Silhouette Score and Davies-Bouldin Index.

4. **Clustering on PCA-Reduced Data:**
   - Apply the same K-Means clustering algorithm to the PCA-transformed dataset.
   - Visualize the clustering results and compare the performance metrics with those from the original dataset.

5. **Comparison and Insights:**
   - Compare the clustering performance based on Silhouette Score and Davies-Bouldin Index for both original and PCA-reduced datasets.
   - Discuss the impact of PCA on clustering performance and data visualization.

## Files

- `wine.csv`: The dataset used in the analysis.
- `pca_clustering_analysis.py`: The Python script containing the code for the analysis.

## Installation

To run this project, you'll need to have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
