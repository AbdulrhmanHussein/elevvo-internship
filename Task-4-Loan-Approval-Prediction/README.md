# 💳 Task 4 – Loan Approval Prediction

## 📌 Overview
Predict whether a loan application will be approved based on applicant details.  
This is a **binary classification problem** where the model must distinguish between approved and not approved applications.  
The challenge also involves handling **imbalanced data**.

## 🗂 Dataset
- Recommended: [Loan Approval Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)  
- Target: Loan_Status (Approved / Rejected)


## ⚙️ Approach
- Data cleaning and handling of missing values  
- Encoding of categorical features (e.g., gender, education, marital status)  
- Train-test split  
- Trained and compared different models:  
  - **Logistic Regression with SMOTE**  
  - **Decision Tree with SMOTE**  
- Addressed class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**  
- Evaluated models using accuracy, precision, recall, F1-score  

## 📈 Results
### 🔹 Logistic Regression (with SMOTE)
- Precision: **0.72**  
- Recall: **0.68**  
- F1-score: **0.70**  
- Served as a strong baseline, but recall was slightly limited.

### 🔹 Decision Tree (with SMOTE)
- Precision: **0.96**  
- Recall: **0.96**  
- F1-score: **0.96**  
- Achieved the best overall performance, showing excellent balance between precision and recall.  

📊 **Key Insights:**  
- **Credit history** and **applicant income** were the most influential features.  
- Handling class imbalance with SMOTE significantly improved both recall and F1-score.  
- The **Decision Tree** clearly outperformed Logistic Regression on this dataset.  

## 🛠 Tools
Python, Pandas, Scikit-learn, Matplotlib, Imbalanced-learn (SMOTE)
