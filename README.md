# Machine Learning Portfolio

A comprehensive collection of machine learning implementations and experiments using popular algorithms and frameworks. This repository contains hands-on implementations of various supervised learning algorithms with real-world datasets.

## 📚 Table of Contents

- [Overview](#overview)
- [Algorithms Implemented](#algorithms-implemented)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository serves as a practical guide to machine learning, featuring implementations of fundamental and advanced algorithms. Each project includes:
- Jupyter notebooks with detailed explanations
- Data preprocessing and exploratory data analysis
- Model training and hyperparameter tuning
- Performance evaluation and visualization
- Real-world datasets

## Algorithms Implemented

### 1. **K-Nearest Neighbors (KNN)**
   - Classification tasks
   - Wine quality prediction
   - GridSearchCV for hyperparameter optimization

### 2. **Linear Regression**
   - Cost prediction models
   - Saline prediction
   - Temperature forecasting
   - Multiple regression implementations

### 3. **Logistic Regression**
   - Binary classification
   - Diabetes prediction
   - Model evaluation with confusion matrix

### 4. **Decision Trees**
   - Classification trees
   - Regression trees
   - Feature importance analysis
   - Applications: diabetes and insurance datasets

### 5. **Random Forests**
   - Ensemble learning
   - Spam detection
   - Feature selection
   - Out-of-bag error estimation

### 6. **Support Vector Machines (SVM)**
   - Classification with different kernels
   - Medical diagnosis (diabetes dataset)
   - Hyperparameter tuning

### 7. **XGBoost**
   - Gradient boosting implementation
   - Classification tasks
   - Regression tasks
   - Advanced ensemble techniques

## Repository Structure

```
MachineLearning/
├── KNN/
│   ├── Classification.ipynb          # Wine quality classification
│   ├── winequality-white.csv
│   └── README.md
├── LinearRegression/
│   ├── CostPrediction.ipynb
│   ├── Salineprediction.ipynb
│   ├── TempPrediction.ipynb
│   └── README.md
├── LogisticRegression/
│   ├── diabetes.ipynb
│   ├── diabetes.csv
│   └── README.md
├── DecisionTrees/
│   ├── ClassificationTree.ipynb
│   ├── RegressorTree.ipynb
│   ├── diabetes.csv
│   ├── insurance.csv
│   └── README.md
├── RandomForests/
│   ├── Detection.ipynb               # Spam detection
│   ├── spam_detection_dataset.csv
│   └── README.md
├── SVM/
│   ├── SVMclassifier.ipynb
│   ├── diabetes.csv
│   └── README.md
├── XGBoost/
│   ├── Classification.ipynb
│   ├── Regressor.ipynb
│   ├── diabetes.csv
│   └── README.md
├── requirements.txt
├── contributing.md
├── LICENSE
└── README.md
```

## Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Jupyter Notebook or JupyterLab

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/MachineLearning.git
   cd MachineLearning
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Navigate to the desired algorithm folder** and open the corresponding `.ipynb` file

3. **Run the cells sequentially** to:
   - Load and explore the dataset
   - Preprocess data
   - Train the model
   - Evaluate performance
   - Visualize results

### Example: Running KNN Classification

```bash
cd KNN
jupyter notebook Classification.ipynb
```


## Technologies Used

- **Python 3.x** - Primary programming language
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Scikit-learn** - Machine learning algorithms and tools
- **XGBoost** - Gradient boosting framework
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter** - Interactive computing environment

## Key Features

✅ **Clean, well-documented code** with explanations  
✅ **Hyperparameter tuning** using GridSearchCV  
✅ **Model evaluation** with multiple metrics  
✅ **Data preprocessing** and feature engineering  
✅ **Visualization** of results and model performance  
✅ **Real-world datasets** for practical learning  

## Contributing

Contributions are welcome! Please refer to [contributing.md](contributing.md) for guidelines on how to contribute to this project.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Author

**Aayam Rimal**

---

⭐ If you find this repository helpful, please consider giving it a star!

## 📫 Contact

For questions, suggestions, or collaborations, feel free to reach out or open an issue.

---

*Last updated: December 2025*