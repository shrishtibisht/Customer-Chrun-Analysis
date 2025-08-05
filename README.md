# 📉 Customer Churn Prediction (IBM Telco Dataset)

> By **Shrishti Bisht** | First End-to-End Data Science Project  
> 🧠 Built with industry-grade ML workflow & storytelling  
> ✅ Logistic Regression & Random Forest | 💾 Model Saved with `joblib`

---

## 🗂️ Overview

Churn in subscription businesses leads to significant revenue loss.  
This project helps **predict customer churn**, **understand why they leave**, and **provide business recommendations** using ML and EDA.

---

## 🎯 Project Goals

- 🔮 Predict customer churn using ML classification
- 📊 Discover patterns in churn behavior via EDA
- ⚖️ Handle class imbalance effectively
- ⚙️ Build and evaluate Logistic Regression & Random Forest models
- 🧾 Deliver business-friendly insights
- 💾 Save the final model for deployment

---

## 📁 Dataset Info

- **Source**: [IBM Telco Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows**: 7,043 customers
- **Target**: `Churn` (Yes/No)
- **Features**: Demographics, billing, contract, internet & phone services

---

## 🛠️ Tools Used

| Tool/Library | Use |
|--------------|-----|
| Python | Core programming |
| Pandas, NumPy | Data wrangling |
| Seaborn, Matplotlib | Visualizations |
| Scikit-learn | ML modeling |
| Joblib | Model saving |
| Notion | Documentation |
| Jupyter Notebook | Project development |

---

## 📊 EDA Highlights

✅ **Key Insights:**

- 📉 Customers with **low tenure** churn more
- 💸 **Month-to-month** contracts show higher churn
- 💰 Customers with **high monthly charges** are more likely to leave
- 🧾 **Paperless billing** customers show more churn
- 📈 **High total charges** = more loyal users

🖼️ *All EDA visualizations are available in the notebook*

---

## ⚖️ Handling Imbalanced Data

- Target class (`Churn`) is **imbalanced** (~26% churners)
- Used **Stratified Train/Test Split**
- Future scope: apply **SMOTE / class weights** for further improvement

---

## 🤖 ML Models Used

### 1. Logistic Regression
- Fast, interpretable baseline
- Good for understanding relationships

### 2. Random Forest
- Captures nonlinearities & interactions
- Better recall and precision for churn class

---

## 📉 Model Evaluation

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 79.3% | 0.56 | 0.59 | 0.59 |
| Random Forest       | 82.6% | 0.67 | 0.71 | 0.69 |

✅ **Random Forest selected** for final deployment

---

## 💼 Business Recommendations

- 🛫 **Improve onboarding** for new customers (0–3 months)
- 🔁 **Convert month-to-month** users to yearly plans
- 💳 **Reward loyal customers** (high total charges)
- 📃 **Clarify paperless billing** process to reduce confusion
- 📞 Prioritize support for **high-charge, short-tenure** customers

---

## 💾 Model Saving (Deployment Ready)

import joblib
joblib.dump(rf_model, "random_forest_churn_model.pkl")


## 🧠 Key Learnings
Built a complete end-to-end ML pipeline

Tackled real-world churn problem

Understood model evaluation beyond accuracy

Made data-driven business suggestions

Learned to communicate results with storytelling

## 📌 Final Reflection
This project helped me move from basic notebooks to solving a business-centric ML problem.
It deepened my understanding of EDA, modeling, and ML deployment basics.
I'm now confident in applying this pipeline to other datasets and use-cases.
