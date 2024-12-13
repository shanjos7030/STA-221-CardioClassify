# STA-221-CardioClassify
CardioClassify: Advanced Machine Learning for ECG-Based Arrhythmia Classification

### Authors and Contributors
Shantanu Joshi, Nikita B. Emberi and V V S Aakash Kotha

## Overview
CardioClassify leverages machine learning and deep learning models (Random Forest, XGBoost, CNN 1D) to classify five arrhythmia types from ECG signals. Using Optuna for hyperparameter optimization, the project achieves high accuracy while identifying key ECG features, offering a comprehensive approach to arrhythmia detection.

## Methodology Pipeline
<img src="https://github.com/user-attachments/assets/dea42773-3792-4210-aa1b-c8cf6f58dcb4" alt="PCA Visualization" width="400"/>

## Results

- **Random Forest Classifier**:
  - Accuracy: 72%
  - Weighted F1-Score: 0.7175
  - AUROC: 0.9236, AUPRC: 0.8041
  - Demonstrated strong feature importance, with PR Segment contributing the most.

- **XGBoost Classifier**:
  - Accuracy: 70%
  - Weighted F1-Score: 0.6939
  - AUROC: 0.9088, AUPRC: 0.7603
  - Competitive performance but slightly below Random Forest.

- **CNN 1D - Experiment 1 (Optuna Optimized)**:
  - Accuracy: 97%
  - Weighted F1-Score: 0.9714
  - AUROC: 0.9983, AUPRC: 0.9940
  - Class-wise Accuracies: Class 0 - 94.52%, Class 1 - 99.21%, Class 2 - 98.92%, Class 3 - 94.62%, Class 4 - 98.34%.

- **CNN 1D - Experiment 2 (Partially Fixed Parameters)**:
  - Accuracy: 98%
  - Weighted F1-Score: 0.9806
  - AUROC: 0.9989, AUPRC: 0.9962
  - Class-wise Accuracies: Class 0 - 95.29%, Class 1 - 99.21%, Class 2 - 99.51%, Class 3 - 97.50%, Class 4 - 98.78%.
 
![image](https://github.com/user-attachments/assets/1511b223-dea8-4d83-83f0-554469452dee)
PCA Visualization of Intermediate Features for CNN 1D Models in Experiment 1 (Left) and Experiment 2 (Right)

## Key Insights:
  - CNN 1D models significantly outperformed classical models (Random Forest, XGBoost) across all metrics.
  - Experiment 2 demonstrated slight performance improvements due to fixed parameter tuning.
  - PCA analysis showcased better feature separability in Experiment 2, highlighting the impact of refined optimization.


