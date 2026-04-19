📊 Clustering & PCA Dimensionality Reduction
📂 Project Overview

This repository contains implementations of two fundamental Unsupervised Machine Learning techniques:

🔹 K-Means Clustering
🔹 Principal Component Analysis (PCA)



📁 1️⃣ Clustering (Clustring.ipynb)
📌 Objective

To group similar data points into clusters using K-Means Clustering.

🧠 Concepts Used
K-Means Algorithm
Elbow Method
Feature Scaling (Standardization)
🔄 Workflow
Generate dataset using make_blobs
Convert into DataFrame
Apply StandardScaler
Use Elbow Method to find optimal K
Train KMeans model
Visualize clusters
📈 Key Highlights
Optimal clusters determined using inertia
Clear visualization of cluster separation
Demonstrates impact of scaling
📁 2️⃣ PCA Dimensionality Reduction (PCADimensions.ipynb)
📌 Objective

To reduce high-dimensional data into lower dimensions while preserving maximum variance.

🧠 Concepts Used
Principal Component Analysis (PCA)
Variance Maximization
Dimensionality Reduction
🔄 Workflow
Generate dataset with 5 features
Apply StandardScaler
Reduce dimensions using PCA (n_components=2)
Convert transformed data into DataFrame
Visualize using scatter plot
📈 Key Highlights
Reduced 5D data → 2D
Retains most important information
Easy visualization of clusters




| Algorithm          | Type         | Purpose                   |
| ------------------ | ------------ | ------------------------- |
| K-Means Clustering | Unsupervised | Group similar data points |
| PCA                | Unsupervised | Reduce dimensionality     |
