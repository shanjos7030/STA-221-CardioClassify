#CardioClassify: Advanced Machine Learning for ECG-Based Arrhythmia Classification**

## Overview
CardioClassify is a comprehensive machine learning framework designed to classify five distinct arrhythmia types based on ECG signals. Leveraging state-of-the-art techniques, the project combines traditional machine learning approaches like Random Forest and XGBoost with deep learning methods using CNN 1D architectures. The primary goal is to achieve accurate arrhythmia classification while gaining insights into the most critical ECG features contributing to predictions.

## Features
- **Classical Machine Learning Models**: Implements Random Forest and XGBoost using extracted time-domain features for arrhythmia classification.
- **Deep Learning with CNN 1D**: Conducts a detailed ablation study using Optuna for hyperparameter optimization.
- **Preprocessing Pipeline**:
  - Balancing the dataset to mitigate class imbalance.
  - Wavelet-based denoising using Symlet wavelets.
  - Z-Score normalization for uniform scaling.
- **Feature Importance Analysis**: Evaluates the importance of ECG features for classification using Random Forest.
- **PCA Visualization**: Visualizes intermediate CNN 1D features for interpretability.
- **Robust Evaluation**: Employs 5-fold cross-validation to ensure model generalizability.

## Contributors
- **Nikita Emberi**
- **Shantanu Joshi**
- **Aakash Kotha**

## Acknowledgments
This project uses the MIT-BIH Arrhythmia Database and NeuroKit for feature extraction.
