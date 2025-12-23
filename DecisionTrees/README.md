# Decision Trees

This folder contains implementations of Decision Tree algorithms for both classification and regression tasks.

---

## Overview

Decision Trees are supervised learning algorithms that recursively partition data based on feature values to create a tree-like model for prediction. They work well for both classification and regression problems.

**Key Characteristics:**
- Easy to interpret and visualize
- Handles both categorical and numerical features
- Prone to overfitting without proper regularization
- No feature scaling required

---

## Contents

This folder includes:
- **Classification notebooks**: Decision tree models for categorical target variables
- **Regression notebooks**: Decision tree models for continuous target variables
- **Datasets**: Sample CSV files for experimentation

## Typical Workflow

1. **Data Preparation**: Load dataset and handle missing values
2. **Feature Engineering**: Select relevant features
3. **Train/Test Split**: Divide data (typically 80/20)
4. **Model Training**: Initialize and fit DecisionTree model
5. **Evaluation**: Assess performance using appropriate metrics
6. **Hyperparameter Tuning**: Adjust tree depth, min samples split, etc. to reduce overfitting

## Common Hyperparameters

- `max_depth`: Maximum depth of the tree
- `min_samples_split`: Minimum samples required to split a node
- `min_samples_leaf`: Minimum samples required at leaf node
- `criterion`: Function to measure split quality (gini, entropy for classification; mse, mae for regression)

## Resources

- [Scikit-learn Decision Tree Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
- [Scikit-learn Decision Tree Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)
