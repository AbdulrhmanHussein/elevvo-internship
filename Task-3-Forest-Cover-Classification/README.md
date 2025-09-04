# 🌲 Task 3 – Forest Cover Type Classification

## 📌 Overview
Predict the type of forest cover based on cartographic and environmental features.  
This is a **multi-class classification problem** where the model must distinguish between several forest cover categories.

## 🗂 Dataset
- Recommended: [Covertype Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/covertype)  
- Target: forest cover type (multi-class)

## ⚙️ Approach
- Data cleaning and preprocessing  
- Encoded categorical features   
- Trained and compared different classifiers:  
  - **Random Forest**  
  - **XGBoost**  
- Performed hyperparameter tuning for improved accuracy  
- Evaluated with accuracy, confusion matrix, and classification report  
- Visualized **feature importance** to understand key predictors  

## 📈 Results
### 🔹 Random Forest Classifier (Tuned)
- **Accuracy:** 0.888  
- Strong performance across most classes  
- Struggled slightly with class 4 (recall = 0.36)  

### 🔹 XGBoost Classifier (Tuned)
- **Accuracy:** 0.842  
- Good balance of precision and recall across classes  
- Also weaker on class 4 (recall = 0.43)  

📊 **Comparison:**  
- Random Forest achieved higher overall accuracy (88.8% vs. 84.2%).  
- XGBoost was competitive but slightly less accurate on this dataset.  
- Both models highlighted **Elevation** and **Soil Type** as key predictive features.  

## 🛠 Tools
Python, Pandas, Scikit-learn, XGBoost, Matplotlib
