# Customer Churn Prediction using Machine Learning

## 📌 Project Overview
This project builds an end-to-end machine learning pipeline to predict customer churn for a subscription-based business. The goal is to identify customers at risk of leaving so that proactive retention strategies can be applied.

The project covers data preprocessing, exploratory analysis, feature engineering, model training, class imbalance handling, and performance evaluation.

---

## 🎯 Business Problem
Customer churn directly impacts revenue. Predicting churn helps businesses:
- Identify high-risk customers early
- Improve retention strategies
- Reduce revenue loss

---

## 🧠 Machine Learning Approach
- Problem Type: Binary Classification
- Target Variable: `churn` (Yes / No)

---

## 📊 Dataset
The dataset contains customer subscription and usage behavior including:
- Subscription plan type
- Monthly fee
- Weekly usage hours
- Support tickets
- Payment failures
- Customer tenure
- Last login recency

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

---

## 🔍 Project Workflow
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering and encoding  
4. Train-test split  
5. Model training (Logistic Regression, Random Forest, XGBoost)  
6. Handling class imbalance using SMOTE  
7. Hyperparameter tuning  
8. Model evaluation using Recall, F1-score, ROC-AUC  
9. Feature importance analysis  
10. Business insights and recommendations  

---

## 🚀 Models Implemented
- Logistic Regression (Baseline)
- Random Forest
- Random Forest + SMOTE
- XGBoost Classifier

---

## 📈 Model Evaluation Metrics
- Accuracy
- Precision
- Recall (priority metric)
- F1-score
- ROC-AUC

---

## 🏆 Key Results
- Tree-based models outperformed Logistic Regression
- SMOTE significantly improved recall for churners
- XGBoost provided strong overall performance and stability

---

## 🔑 Key Business Insights
- Customers with low usage and high inactivity are more likely to churn
- Payment failures strongly correlate with churn
- Longer-tenure customers churn less frequently

---

## 📁 Repository Structure
