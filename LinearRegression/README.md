# Linear Regression Projects

This repository contains three linear regression projects demonstrating workflow, data cleaning, modeling, and evaluation using real-world datasets.

---

## 1. Predicting Max Temperature from Min Temperature (World War 2 Weather Dataset)

**Overview:**  
- Goal: Predict daily maximum temperature using minimum temperature as the feature.  
- Dataset link: https://www.kaggle.com/datasets/smid80/weatherww2/data

**Workflow:**  
1. Data Cleaning: Dropped missing values.  
2. Feature Selection: Only `MinTemp` used to predict `MaxTemp`.  
3. Train/Test Split: 80/20 split.  
4. Linear Regression: Trained `LinearRegression` model.  
5. Evaluation: Calculated R² and RMSE to measure performance.  

**Results:**  
- The model achieved an R² of 0.77 indicating moderate predictive ability.  
- Demonstrates the effectiveness of simple linear regression with a **single feature**.

---

## 2. Ocean Salinity Prediction (Depth and Temperature)

**Overview:**  
- Goal: Predict **Salinity (Salnty)** using **Depth (Depthm)** and **Temperature (T_degC)**.  
- Dataset link: https://www.kaggle.com/datasets/sohier/calcofi?select=bottle.csv

**Workflow:**  
1. Data Cleaning: Dropped ~2.3% rows with missing values.  
2. Sampling: Randomly sampled 20,000 rows for faster experimentation.  
3. Train/Test Split: 80/20 split.  
4. Linear Regression: Trained `LinearRegression` model.  
5. Evaluation: Calculated R² to assess performance.  

**Results:**  
- R² ≈ 0.6(improved from 0.3), showing that non linear relationship increased model score.
- Highlights the importance of more features or non-linear models for complex targets.

**Insights:**  
- Linear regression is useful as a baseline.  
- Low R² reflects **dataset limitations** which was fixed with polynomial regression, not modeling mistakes. 
- Potential improvements:
  - Include additional features (latitude, longitude, season, pressure).  
  - Add interaction or polynomial terms.  
  - Explore tree-based or ensemble models.

## 3. Insurance charge prediction

**Overview:**  
- Goal: Predict insurance charges from age,bmi,childrens and smoking habit 
- Dataset link: https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset

**Workflow:**  
1. Data Cleaning
2. Feature Selection:Selected useful features and labelencoded **smoking** for better results. 
3. Train/Test Split: 80/20 split.  
4. Linear Regression: Trained `LinearRegression` model.  
5. Evaluation: Calculated R² and RMSE to measure performance.  

**Results:**  
- The model achieved an R² of 0.86 indicating good predictive ability.  
- Demonstrates the effectiveness of simple linear regression with multiple features and polynomial features.


---

## How to Run

1. Clone the repository
- git clone 

2. Install dependencies
- pip install -r requirements.txt

3. Run individual scripts or notebooks
 - World War 2 Weather
 - Ocean Salinity Prediction
 - Insurance charge prediction
