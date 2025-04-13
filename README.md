# NDVI-Based Crop Classification for Rice and Cotton



This project applies machine learning techniques to classify rice and cotton crops based on their NDVI (Normalized Difference Vegetation Index) values. Leveraging both supervised and unsupervised learning algorithms, the project aims to enhance agricultural management, resource allocation, and policy formulation.

## Table of Contents

- [Contributors](#contributors)
- [Introduction](#introduction)
- [Features](#features)
- [Algorithms and Techniques](#algorithms-and-techniques)
- [Results](#results)


---
## Contributors


- **Muhammad Sarmad Saleem(MSS)**
- **Tayyab Raza**

## Instructor

--**Dr. Muhammad Moazam Fraz**


## Introduction

Effective crop classification is crucial for agricultural planning. This project uses time-series NDVI data spanning three years to classify crops using supervised and unsupervised machine learning methods. The dataset highlights the spectral differences between rice and cotton, enabling precise classification and aiding in resource optimization.

## Features

- **Supervised Learning Algorithms**: Implemented XGBoost, Random Forest, SVM, and Bagging.
- **Unsupervised Learning Algorithms**: Applied K-Means, Hierarchical Clustering, DBSCAN, and Gaussian Mixture Models.
- **Cross-Validation**: Three-year data split for rigorous evaluation.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) for unsupervised learning.
- **Hyperparameter Optimization**: Grid Search for tuning algorithm parameters.
- **Data Handling**: Strategies to mitigate class imbalance using SMOTE and augmentation.

## Algorithms and Techniques

### Supervised Learning:
- **XGBoost**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **Bagging (Bootstrap Aggregation)**

### Unsupervised Learning:
- **K-Means Clustering**
- **Hierarchical Clustering**
- **DBSCAN**
- **Gaussian Mixture Models**

### Evaluation Metrics:
- Accuracy, Precision, Recall, F1-Score, and Confusion Matrix for supervised learning.
- Cluster Purity and Confusion Matrix for unsupervised learning.



## Results

- **Supervised Learning**: Achieved high accuracy and F1-scores for both rice and cotton classification.
- **Unsupervised Learning**: Effective clustering of NDVI data using PCA and without PCA.
- **Feature Importance**: Highlighted significant features using Random Forest and XGBoost.
To view results visit both notebooks for supervised and unsupervised results

---

Feel free to explore and contribute to this project! For inquiries or feedback, please open an issue or contact the contributors.

---




_This project was developed as part of the CS471 Machine Learning course at NUST, SEECS._
