# K-Means Clustering: Customer Segmentation

## Overview
This project uses K-Means clustering to segment mall customers based on their demographic and behavioral data. The goal is to identify distinct customer groups to enable targeted marketing strategies.

## Dataset
- **File:** `Mall_Customers.csv`
- **Features:**
  - Age
  - Gender
  - Annual Income (k$)
  - Spending Score (1-100)

## Methodology

### 1. Data Preprocessing
- Removed customer IDs
- Standardized features using StandardScaler (required for K-Means as it's distance-based)
- Selected numerical features: Age, Income, and Spending Score

### 2. Optimal Cluster Selection
- **Elbow Method:** Plotted inertia across k values (2-10)
- **Silhouette Score:** Evaluated cluster quality for each k value
- Selected optimal k based on highest silhouette score

### 3. Model Training
- Applied K-Means algorithm with optimal clusters
- Used k-means++ initialization for better centroid placement
- Assigned cluster labels to each customer

### 4. Analysis & Visualization
- Calculated cluster statistics (average income and spending score per segment)
- Visualized customer segments using scatter plots
- Evaluated model performance using silhouette score

## Results
The analysis identified distinct customer segments with different income and spending patterns, which can be used for:
- Targeted marketing campaigns
- Product recommendations
- Customer retention strategies
- Resource allocation

## Technologies Used
- Python 3.x
- pandas - Data manipulation
- scikit-learn - K-Means implementation, preprocessing, and evaluation
- matplotlib - Data visualization

## How to Run
1. Ensure all dependencies are installed:
   ```bash
   pip install pandas scikit-learn matplotlib
   ```
2. Open `Pattern.ipynb` in Jupyter Notebook or VS Code
3. Run all cells sequentially

## Key Takeaways
- Feature scaling is crucial for K-Means clustering
- Multiple evaluation metrics provide better model selection
- Visual analysis helps interpret cluster characteristics
- Customer segmentation enables data-driven business decisions
