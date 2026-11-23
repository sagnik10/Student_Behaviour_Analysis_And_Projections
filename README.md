<!-- SAGNIK10-STYLE-HEADER -->
<div align="center">
  <a href="https://github.com/sagnik10"><img src="https://img.shields.io/badge/Sagnik_Sen-Data%20Analytics%20%26%20ML-275cce?style=flat-square" alt="Category" /></a>
  <img src="https://img.shields.io/badge/Stack-Python-192a43?style=flat-square" alt="Stack" />
  <img src="https://img.shields.io/badge/License-MIT-54647a?style=flat-square" alt="License" />
</div>

<p align="center">
  <a href="https://sagnik10.github.io/SagnikSenPortfolio/">Portfolio</a> ·
  <a href="https://github.com/sagnik10">GitHub Profile</a> ·
  <a href="https://github.com/sagnik10/sagnik-sen-antigravity-plugin">Antigravity Plugin</a>
</p>

---
<!-- /SAGNIK10-STYLE-HEADER -->
# Student Behavioural Analysis Intelligence – Kaggle Edition

Production-grade automated analytics pipeline designed for Kaggle datasets.  
This repository builds a full structural intelligence workflow from raw CSV input to model artifacts, charts, similarity recommendations, and a generated PDF report.

---

## Overview

This project automatically:

- Detects dataset schema dynamically
- Identifies numeric features
- Selects a target variable
- Applies preprocessing and scaling
- Performs structural dimensionality reduction (PCA)
- Detects anomalies (Isolation Forest)
- Performs clustering diagnostics (KMeans + Silhouette Score)
- Conducts spectral frequency analysis (Periodogram)
- Computes rolling statistics and volatility
- Ranks feature importance (Mutual Information)
- Generates cosine-similarity recommendations
- Produces a structured PDF intelligence report
- Exports charts and model artifacts

All without hardcoding dataset-specific assumptions.

---

## Folder Structure

```
Output/
│
├── charts/
│   ├── pca_variance.png
│   ├── pca_projection.png
│   ├── anomaly.png
│   ├── cluster.png
│   ├── fourier.png
│   ├── rolling_mean.png
│   ├── rolling_volatility.png
│   ├── cumulative_growth.png
│   ├── correlation.png
│   ├── distribution.png
│   └── feature_importance.png
│
├── models/
│   ├── scaler.pkl
│   └── pca.pkl
│
├── recommendations/
│   └── entity_similarity_recommendations.csv
│
└── Intelligence_Report.pdf
```

---

## Features

### 1. Automated Schema Detection
- Dynamically reads CSV from Kaggle input
- Normalizes column names
- Automatically extracts numeric features
- Automatically determines target variable

### 2. Preprocessing
- Median imputation for missing values
- Standard scaling
- Model persistence via pickle

### 3. Structural Analysis
- PCA decomposition
- Cumulative explained variance visualization
- 2D projection mapping

### 4. Anomaly Detection
- Isolation Forest
- Visual anomaly mapping

### 5. Clustering
- KMeans clustering
- Silhouette score evaluation
- Cluster visualization in PCA space

### 6. Spectral Analysis
- Detrended signal
- Frequency domain power spectrum
- Log-scaled power plot

### 7. Rolling Intelligence
- Adaptive rolling window
- Trend mean tracking
- Volatility estimation

### 8. Feature Importance
- Mutual Information regression ranking
- Horizontal importance chart

### 9. Similarity Engine
- Cosine similarity matrix
- Top-5 nearest entity recommendations
- Exported as CSV

### 10. Automated PDF Reporting
- Executive summary
- Cluster quality metrics
- Execution time
- All generated charts embedded
- Fully reproducible report

---

## Installation

### Kaggle Notebook
```bash
!pip install -q numpy pandas matplotlib seaborn scipy scikit-learn reportlab
```

### Local Environment
```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn reportlab
```

---

## Usage (Kaggle)

1. Upload dataset to Kaggle.
2. Place script in notebook.
3. Run.
4. Output will be available in:

```
/kaggle/working/Output
```

---

## Execution Output

- Processed dataset
- Scaler model
- PCA model
- Structural charts
- Similarity recommendations
- Full PDF Intelligence Report

---

## Design Philosophy

This project follows:

- Dynamic adaptability (no dataset hardcoding)
- Reproducibility
- Structural data diagnostics
- Model persistence
- Automated reporting
- Production-grade organization

It is designed for rapid exploratory intelligence generation across arbitrary tabular datasets.

---

## Repository

GitHub:  
https://github.com/sagnik10/automated-dataset-intelligence-kaggle

---

## Author

Sagnik  
Project Scientist I  
India Meteorological Department  

---

## License

MIT License


<!-- SAGNIK10-STYLE-FOOTER -->
---
<p align="center">
  Maintained by <a href="https://github.com/sagnik10"><strong>Sagnik Sen</strong></a> ·
  <a href="https://sagnik10.github.io/SagnikSenPortfolio/">Portfolio &amp; 1-on-1 Teaching</a> ·
  <a href="https://www.linkedin.com/in/sagnik-sen-0a70431a8/">LinkedIn</a>
</p>
<!-- /SAGNIK10-STYLE-FOOTER -->