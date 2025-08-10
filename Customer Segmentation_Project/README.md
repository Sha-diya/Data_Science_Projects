# Customer Segmentation Project

## Overview

This project employs machine learning techniques to segment customers based on their purchasing behavior and demographics. By identifying distinct customer groups, businesses can tailor marketing strategies, enhance customer satisfaction, and optimize resource allocation.

## Project Highlights

- **Dataset**: Utilizes a customer dataset containing attributes such as age, annual income, and spending score.
- **Objective**: To categorize customers into meaningful segments using clustering algorithms.
- **Techniques**: Data preprocessing, exploratory data analysis (EDA), feature scaling, and clustering using K-Means.
- **Tools**: Python, Jupyter Notebook, pandas, NumPy, scikit-learn, matplotlib, seaborn.

## Methodology

1. **Data Preprocessing**  
   - Loaded the dataset and handled missing values.  
   - Encoded categorical variables if necessary.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and relationships between variables.  
   - Identified patterns and outliers.

3. **Feature Scaling**  
   - Standardized features to ensure uniformity, especially for distance-based algorithms like K-Means.

4. **Clustering**  
   - Applied the K-Means algorithm to segment customers.  
   - Determined the optimal number of clusters using the Elbow Method.

5. **Visualization**  
   - Visualized clusters using 2D and 3D plots to interpret the segmentation.

## Getting Started

### Prerequisites

Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Running the Notebook
1. Clone the repository:
```bash
git clone https://github.com/Sha-diya/Data_Science_Projects.git
```
2. Navigate to the project directory:
```bash
cd Data_Science_Projects/Customer_Segmentation_Project
```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```
4. Open `customer_Segmentation.ipynb` and run the cells sequentially.


## Results
The clustering analysis revealed distinct customer segments with varying purchasing behaviors. These insights can inform targeted marketing campaigns and personalized customer experiences.
