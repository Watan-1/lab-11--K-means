# lab-11--K-means
# Credit Card Customer Segmentation using K-Means

---

## Objectives
- Perform customer segmentation using K-Means clustering
- Explore customer behavior patterns
- Use the Elbow Method and Silhouette Score to select the best number of clusters
- Visualize customer groups using PCA

---

## Dataset
The dataset used is `CC_GENERAL.csv`.
The dataset contains customer credit card usage information such as:

- BALANCE
- PURCHASES
- CASH_ADVANCE
- CREDIT_LIMIT
- PAYMENTS
- TENURE
- and other financial features

---

## Steps Performed

### 1. Data Loading
- Loaded the dataset using Pandas

### 2. Data Cleaning
- Removed the `CUST_ID` column
- Checked missing values
- Filled missing values using mean imputation

### 3. Exploratory Data Analysis
- Histograms
- Scatter plots
- Correlation heatmap

### 4. Feature Scaling
- Applied `StandardScaler`

### 5. K-Means Clustering
- Tested different K values
- Used:
  - Elbow Method
  - Silhouette Score

### 6. Final Model
- Trained the final K-Means model
- Assigned cluster labels to customers

### 7. Visualization
- Visualized clusters using PCA

---

## Results
The model successfully grouped customers into different segments based on spending behavior, balance, and cash advance usage.

These clusters can help businesses:
- Improve marketing strategies
- Identify high-value customers
- Understand customer behavior
- Personalize offers and services

