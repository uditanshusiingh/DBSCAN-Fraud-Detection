# DBSCAN-Fraud-Detection
# 💳 DBSCAN-Based Anomaly Detection in Financial Transactions

This project applies **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to detect anomalies in financial transaction data — specifically, potential credit card fraud.

## 📌 Overview

- **Goal**: Identify outliers (potential frauds) in credit card transaction data using unsupervised learning.
- **Algorithm**: DBSCAN (no need to predefine cluster count, great at detecting noise).
- **Dataset**: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Evaluation Metrics**:
  - Silhouette Score (core cluster quality)
  - Davies–Bouldin Index (cluster compactness)
  - Precision/Recall (optional, with true fraud labels)

---

## 🧪 Features

- Data preprocessing and standardization
- Dimensionality reduction using PCA
- k-distance plot to choose optimal `eps` for DBSCAN
- Visualization of clusters and outliers
- Optional validation against known fraud labels

---

## 📁 Files

```bash
.
├── dbscan_fraud.py         # Main Python script
├── creditcard.csv          # Dataset (not included due to size; download from Kaggle)
├── requirements.txt        # Required Python packages
└── README.md               # This file
