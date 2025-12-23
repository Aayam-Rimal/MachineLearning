# K-Nearest Neighbors (KNN)

This folder contains implementations of the K-Nearest Neighbors algorithm for classification and regression tasks.

---

## Overview

K-Nearest Neighbors (KNN) is a simple, non-parametric algorithm that classifies or predicts based on the K closest training examples in the feature space. It's instance-based learning where predictions are made directly from training data.

**Key Characteristics:**
- Simple to understand and implement
- No explicit training phase - stores entire training dataset
- Lazy learner (computation happens at prediction time)
- Sensitive to feature scaling
- Performance depends heavily on distance metric and K value

---

## Contents

This folder includes:
- **Classification notebooks**: KNN models for categorical predictions
- **Regression notebooks**: KNN models for continuous value predictions
- **Datasets**: Sample CSV files for experimentation

## Typical Workflow

1. **Data Preparation**: Load dataset and handle missing values
2. **Feature Scaling**: Normalize/standardize features (important for KNN)
3. **Train/Test Split**: Divide data (typically 80/20)
4. **Model Training**: Initialize KNN with chosen K value
5. **Evaluation**: Assess performance using appropriate metrics
6. **K Optimization**: Find optimal K through cross-validation

## Key Hyperparameters

- `n_neighbors`: Number of nearest neighbors to consider
- `weights`: How to weight neighbors (uniform or distance-weighted)
- `metric`: Distance metric (euclidean, manhattan, minkowski, etc.)
- `algorithm`: Search method (ball_tree, kd_tree, brute)

## Common Pitfalls

- **High dimensionality**: KNN struggles with many features (curse of dimensionality)
- **Imbalanced data**: Majority class can dominate predictions
- **Feature scaling**: Different scales can bias distance calculations
- **Large datasets**: Can be slow and memory-intensive

## Resources

- [Scikit-learn KNN Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
- [Scikit-learn KNN Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html)
