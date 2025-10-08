# Voice Gender Recognition using Unsupervised Learning

A machine learning project that implements voice gender classification using unsupervised clustering algorithms. This project demonstrates how clustering techniques can naturally separate male and female voices based on acoustic features without labeled training data.

## 🎯 Project Overview

This project analyzes voice samples using various unsupervised clustering algorithms to distinguish between male and female voices. By leveraging acoustic features like frequency, spectral characteristics, and modulation patterns, the system achieves **64% accuracy** in gender classification without any supervised training.

## ✨ Features

- **Multiple Clustering Algorithms**: K-Means, DBSCAN, Hierarchical Clustering, Gaussian Mixture Models
- **Comprehensive Feature Analysis**: 20+ acoustic parameters including mean frequency, spectral entropy, modulation index
- **Performance Evaluation**: Silhouette scores, Adjusted Rand Index, cluster distribution analysis
- **Visualization**: PCA-based cluster visualization, feature importance analysis
- **Optimal Cluster Detection**: Elbow method and silhouette analysis for determining ideal cluster count

## 🛠️ Technical Stack

- **Python** with scikit-learn, pandas, numpy
- **Clustering Algorithms**: K-Means, DBSCAN, Agglomerative Clustering, GMM
- **Visualization**: matplotlib, seaborn, PCA
- **Data Processing**: StandardScaler, feature engineering

## 📊 Results

- **Best Algorithm**: K-Means Clustering
- **Accuracy**: 64% (unsupervised)
- **Key Features**: mean frequency, spectral entropy, modulation characteristics
- **Cluster Separation**: Clear natural grouping of male vs female voices

## 🚀 Getting Started

```bash
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn
pip install librosa
pip install numba audioread soundfile
pip install openpyxl xlrd
pip install pandas numpy scikit-learn matplotlib seaborn librosa numba audioread soundfile openpyxl xlrd
