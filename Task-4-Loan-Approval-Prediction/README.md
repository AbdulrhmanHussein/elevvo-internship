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
- Trained and compared models:  
  - **Logistic Regression (baseline)**  
  - **Logistic Regression with SMOTE**  
  - **Decision Tree with SMOTE**  
- Addressed class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**  
- Evaluated models using accuracy, precision, recall, F1-score  

## 📈 Results
### 🔹 Logistic Regression (without SMOTE)
- Precision: **0.79**  
- Recall: **0.36**  
- F1-score: **0.50**  
- The model was biased toward the majority class, failing to capture many positive loan approvals.

### 🔹 Logistic Regression (with SMOTE)
- Precision: **0.72**  
- Recall: **0.68**  
- F1-score: **0.70**  
- Performance improved significantly after balancing the dataset with SMOTE.  

### 🔹 Decision Tree (with SMOTE)
- Precision: **0.96**  
- Recall: **0.96**  
- F1-score: **0.96**  
- Best-performing model, showing excellent balance and robustness.  

📊 **Key Insights:**  
- **Credit history** and **applicant income** were the strongest predictors.  
- Handling class imbalance with SMOTE was critical to achieving good recall and F1-score.  
- Ensemble or tree-based models (Decision Tree, Random Forest) performed far better than linear models on this dataset.  

## 🛠 Tools
Python, Pandas, Scikit-learn, Matplotlib, Imbalanced-learn (SMOTE)
