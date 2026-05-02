# -Telecom-Customer-Churn-Prediction-System
A telecom churn prediction project using multiple ML models, with XGBoost as the final model, focused on high recall and identifying high-risk customers for business insights.

# 📡 Telecom Customer Churn Prediction System

##  Project Overview

This project focuses on predicting customer churn in the telecom industry using machine learning techniques. The goal is to identify customers who are likely to leave the service, enabling businesses to take proactive retention actions.

The system uses multiple machine learning models and selects the best-performing model (XGBoost) based on evaluation metrics, with a focus on recall to effectively capture high-risk churn customers.

---

## Objectives

* Predict whether a customer will churn or stay
* Identify high-risk customers using probability scores
* Provide actionable insights for customer retention
* Build a business-oriented prediction system

---

## Machine Learning Approach

### 🔹 Models Used

* Logistic Regression
* Random Forest
* Gradient Boosting
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* ⭐ XGBoost (Final Model)

### Techniques Applied

* Data Cleaning & Preprocessing
* Feature Engineering
* One-Hot Encoding
* Feature Scaling (MinMaxScaler)
* SMOTE (Handling Class Imbalance)
* Hyperparameter Tuning (GridSearchCV)
* Threshold Optimization (Improving Recall)

---

## Model Performance (XGBoost)

* **Accuracy:** ~84%
* **Precision:** ~81%
* **Recall:** ~88% ⭐
* **F1 Score:** ~84%

> The model is optimized for recall to ensure maximum detection of churn customers.

---

## Key Features

* Model comparison with multiple algorithms
* ROC Curve & Confusion Matrix visualization
* Risk Segmentation (High / Medium / Low)
* Business insights and churn distribution
* Exportable predictions (`churn_predictions.csv`)
* Identification of top high-risk customers

---

## Business Insights

* Customers with higher monthly charges are more likely to churn
* Short tenure customers show higher churn probability
* Lack of technical support increases churn risk

The model predicts churn probability and segments customers into risk levels:

* 🔴 High Risk → Immediate action required
* 🟡 Medium Risk → Retention strategies recommended
* 🟢 Low Risk → Monitoring only

---

## Dataset

* 📌 Dataset: IBM Telco Customer Churn Dataset
* Source: Kaggle
* Features include:

  * Tenure
  * MonthlyCharges
  * TotalCharges
  * Contract Type
  * Internet Service
  * Tech Support
  * Churn (Target Variable)

---

## Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn
* Google Colab

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook / Colab:

```bash
run the notebook
```

4. Run all cells to:

* Train models
* Evaluate performance
* Generate predictions

---

## Output Files

* `churn_predictions.csv` → Full prediction dataset
* Contains:

  * Actual vs Predicted
  * Churn Probability
  * Risk Level

## Project Highlights

✔ End-to-end ML pipeline
✔ Multi-model comparison
✔ Business-focused predictions
✔ Risk-based customer segmentation
✔ High recall for churn detection


## 👩‍💻 Author

**Varshitha Darmini**
AI/ML Student

🔗 GitHub: https://github.com/VarshithaDarmini
