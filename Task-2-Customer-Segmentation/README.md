# 🛒 Task 2 – Customer Segmentation

## 📌 Overview
Cluster mall customers into meaningful groups based on their annual income and spending score.  
The goal is to identify customer segments that can help businesses target marketing strategies effectively.

## 🗂 Dataset
- Recommended: [Mall Customer Dataset (Kaggle)]([https://www.kaggle.com/](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python))  
- Features: CustomerID, Age, Gender, Annual Income, Spending Score  

## ⚙️ Approach
- Data cleaning and preprocessing  
- Exploratory data analysis with scatter plots and histograms  
- Feature scaling for clustering  
- Applied **K-Means Clustering**  
- Used the **Elbow Method** to find the optimal number of clusters  
- Visualized clusters in 2D
- Applied **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**  

## 📈 Results
- DBSCAN automatically discovered clusters without requiring a predefined number.  
- It also identified some customers as **outliers/noise**, which K-Means cannot handle.  
- Found groups such as:  
  - High-income frequent spenders  
  - Budget-conscious customers  
  - Moderate spenders with mid-level income  



## 🛠 Tools
Python, Pandas, Matplotlib, Seaborn, Scikit-learn
