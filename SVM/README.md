# Support Vector Machines (SVM)

This folder contains implementations of Support Vector Machines for classification and regression tasks.

---

## Overview

Support Vector Machine (SVM) is a powerful supervised learning algorithm that finds the optimal hyperplane to separate classes (classification) or fit data points (regression). It works well in high-dimensional spaces and is effective for both linear and non-linear problems.

**Key Characteristics:**
- Effective in high-dimensional spaces
- Memory efficient (uses subset of training data - support vectors)
- Versatile through different kernel functions
- Requires feature scaling for optimal performance
- Can handle non-linear problems with appropriate kernels
- Computationally expensive for very large datasets

---

## Contents

This folder includes:
- **Classification notebooks**: SVM models for categorical predictions
- **Regression notebooks**: SVM models for continuous value predictions
- **Datasets**: Sample CSV files for experimentation

## Typical Workflow

1. **Data Preparation**: Load dataset and handle missing values
2. **Feature Scaling**: Normalize/standardize features (critical for SVM)
3. **Train/Test Split**: Divide data (typically 80/20)
4. **Kernel Selection**: Choose appropriate kernel (linear, rbf, poly, sigmoid)
5. **Model Training**: Initialize and fit SVM model
6. **Evaluation**: Assess performance using appropriate metrics
7. **Hyperparameter Tuning**: Optimize C, gamma, kernel parameters

## Key Hyperparameters

- `C`: Regularization parameter (higher = fit training data more closely)
- `kernel`: Kernel function (linear, rbf, poly, sigmoid)
- `gamma`: Kernel coefficient for rbf, poly, sigmoid kernels
- `degree`: Degree for polynomial kernel
- `epsilon`: Tolerance for regression error (SVR only)
- `probability`: Enable probability estimates

## Kernel Functions

- **Linear**: For linearly separable data, fast and interpretable
- **RBF (Radial Basis Function)**: For non-linear problems, most versatile
- **Polynomial**: For polynomial boundaries, degree parameter controls complexity
- **Sigmoid**: Similar to neural network activation

## Important Considerations

- **Feature Scaling**: Essential for good performance
- **Class Imbalance**: Use class weights to handle imbalanced data
- **Computational Cost**: Can be slow with large datasets
- **Hyperparameter Tuning**: Critical for optimal performance

## Advantages

- Effective in high-dimensional spaces
- Memory efficient
- Versatile with different kernels
- Robust to overfitting with proper regularization

## Resources

- [Scikit-learn SVM Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
- [Scikit-learn SVM Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)
