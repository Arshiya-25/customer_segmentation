# CUSTOMER SEGMENTATION ANALYSIS
This repository explores advanced customer segmentation techniques using three machine learning approaches: K-Means Clustering, Gaussian Mixture Models (GMM), and GMM enhanced with Explainable AI (XAI) tools.
## Project Overview 
The aim of this project is to segment mall customers based on behavioral and demographic features to enable better marketing strategies and personalized engagement.
## Methodology 
### 1. K-Means Clustering
- **Technique**: Centroid-based clustering
- **Key Features**:
  - `StandardScaler` for feature normalization
  - Elbow Method for determining optimal number of clusters
  - Silhouette Score for cluster validation
- **Performance Metrics**:
  - Optimal clusters selected using Elbow and Silhouette methods
  - Assesses cluster quality and separation
### 2. Gaussian Mixture Model (GMM)
- **Technique**: Probabilistic soft clustering
- **Key Features**:
  - Bayesian Information Criterion (BIC) for selecting optimal components
  - Can model elliptical and overlapping clusters
- **Performance Metrics**:
  - Optimal component selection using BIC
  - Cluster membership probabilities for interpretability
### 3. GMM with Explainable AI (XAI)
- **Technique**: Interpretable clustering analysis
- **Explainability Methods**:
  - **SHAP**: Global feature importance for all clusters
  - **LIME**: Local explanations for individual customer predictions
- **Key Insights**:
  - Understand the reasoning behind cluster assignments
  - Clear visualization of customer segment characteristics
## Dependencies
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- SHAP
- LIME
## Use Cases
- Smarter customer targeting
- Better understanding of customer behavior
- More personalized offers and services
