# Customer Segmentation Project

## Overview
This project uses **machine learning** to perform **customer segmentation**, enabling businesses to identify distinct customer groups based on demographics and spending behavior for targeted marketing strategies.

## Dataset Information
- **`Mall_Customers.csv`** contains demographic and behavioral data, typically including:
  - `CustomerID`: Unique identifier for each customer
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## Notebook Overview — `Customer_Segmentation.ipynb`
### 1️⃣ Data Loading & Preprocessing
- Load and inspect the dataset.
- Handle missing values and duplicates.
- Scale features were required for clustering.

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualize feature distributions (age, income, spending patterns).
- Understand relationships between features.

### 3️⃣ Determining Optimal Clusters
- **Elbow Method** to assess within-cluster variance.
- **Silhouette Score** or **Gap Statistic** (optional) for cluster quality validation.

### 4️⃣ Clustering with K-Means
- Apply **K-Means** clustering with the optimal number of clusters.
- Assign cluster labels to each customer.

### 5️⃣ Cluster Interpretation & Visualization
- Calculate average feature values per cluster.
- Create scatter plots and bar plots to understand each segment.

### 6️⃣ Insights & Recommendations
- Identify **high-income, high-spending** customers for premium marketing.
- Recognize **low-income, low-spending** customers for budget campaigns.


## How to Use
1. Clone the repository:
   ```bash
   git clone <repo_link>
   ```
2. Open `Customer_Segmentation.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells to view analysis, visualizations, and insights.
4. Modify clustering parameters or explore additional datasets as needed.


## Outcomes & Takeaways
- Found distinct customer segments based on income, spending score, and demographics.
- Provided actionable marketing insights for targeted campaigns.
- Delivered a reusable machine learning framework for customer segmentation tasks.
