# 🔄 Customer Churn Prediction

## 📘 Project Overview

Customer churn—when a customer ends their relationship with a company—is one of the most pressing challenges businesses face today. Understanding and predicting which customers are likely to churn can help companies implement **retention strategies** and **minimize revenue loss**.

This project focuses on building a **classification model** to predict customer churn based on customer demographics, account details, and the services they use. With machine learning, we aim to identify high-risk customers and empower businesses to act before they leave.

---

## 🎯 Problem Statement

The objective of this project is to:
- **Predict whether a customer will churn or not** using classification models.
- Use **demographic, account, and service usage data** to build accurate and interpretable models.
- Derive actionable insights to help the company **retain valuable customers** and reduce attrition.

---

## 🗂️ Dataset Information

- **Dataset Name**: `Customer_data` [Dataset](https://docs.google.com/spreadsheets/d/1rnBO9F9xdSUY-WpeOJilMxMRZT-hwwWq6O98OHreY0k/edit?usp=sharing)
- The dataset includes features such as:
  - **Demographics**: Gender, Senior Citizen, Partner, Dependents
  - **Account Info**: Tenure, Monthly Charges, Total Charges
  - **Services**: Internet Service, Online Security, Streaming TV, Phone Service
  - **Target Variable**: `Churn` (Yes/No)

Detailed schema can be found in the **[Data Information](https://docs.google.com/document/d/1V-L3EdEnEEiYHhxppRY_CkPRbJ77ELYc/edit?usp=sharing&ouid=103283051675327639429&rtpof=true&sd=true)** document.

---

## 📌 Deliverables

### 1. 🔍 Data Exploration & Preprocessing
- Handle missing values and data types.
- Perform feature encoding, transformation, and scaling.
- Analyze class imbalance and perform necessary balancing techniques.

### 2. 🧠 Model Development
- Build and compare various classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost / Gradient Boosting
- Apply hyperparameter tuning for performance optimization.

### 3. 📏 Model Evaluation 
Evaluate model performance using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

---

## 🛠️ Tools & Technologies

- **Python**
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`, `seaborn`
- **Jupyter Notebook** (or any Python IDE)

---

## 🔄 Methodology

1. **Data Cleaning**
   - Null handling, type correction, and outlier detection.

2. **Feature Engineering**
   - Label encoding for categorical features.
   - Creating derived features such as average revenue per tenure.

3. **Model Training**
   - Train-test split for robust evaluation.
   - Use GridSearchCV or RandomizedSearchCV for hyperparameter tuning.

4. **Evaluation**
   - Focus on recall and precision to identify churn cases correctly.
   - Use visualizations like ROC curve and confusion matrix.

5. **Interpretation**
   - Analyze feature importance using models like Random Forest or SHAP.

---

## 👨‍💻 Author

**Rahul Yadav**  
Aspiring Data Scientist | Machine Learning | Predictive Modeling | Business Insights  
[LinkedIn](https://www.linkedin.com/in/rahulyadav2707/)
