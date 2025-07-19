
# 📉 Customer Churn Prediction

A full machine learning and data analytics project focused on predicting customer churn using demographic, service, and account-related data. This project is designed to demonstrate practical skills in preprocessing, model building, evaluation, and business insight generation.

---

## 📌 Problem Statement

Customer churn is a significant challenge for subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones. By predicting churn, companies can proactively take measures to retain at-risk customers.

---

## 🎯 Objectives

- Explore and clean the dataset
- Handle class imbalance using resampling techniques
- Train and compare multiple ML models and a deep learning model
- Evaluate performance using F1 Score, Accuracy, and Confusion Matrix
- Visualize feature importance and model performance
- Provide actionable business recommendations

---

## 🗃️ Dataset

The dataset includes customer data such as:

- Demographics (e.g., gender, senior citizen)
- Service plans (e.g., phone, internet, contract type)
- Billing information (e.g., monthly charges, total charges)
- Churn label (whether the customer left or not)

---

## 🧠 Models Used

- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- Deep Learning (Neural Network using Keras/TensorFlow)

---

## 📈 Results

| Model              | Accuracy | F1 Score |
|--------------------|----------|----------|
| Logistic Regression| 0.79     | 0.61     |
| Random Forest      | 0.76     | 0.53     |
| Deep Learning      | TBD      | TBD      |

*Note: Scores may vary based on hyperparameters and random seed.*

---

## ✅ Conclusion

- Churn is influenced by contract type, tenure, and billing amount.
- Logistic Regression performed well due to the linearly separable nature of the data.
- Balancing the dataset with RandomOverSampler improved model recall on the minority class (churned customers).

---

## 📌 Recommendations

- Offer long-term contracts to month-to-month customers
- Provide incentives to high-charge customers with short tenure
- Monitor and re-train the model with new data periodically

---

## 🧰 Tools & Libraries

- Python (Pandas, NumPy)
- Scikit-learn
- Imbalanced-learn
- Matplotlib & Seaborn
- TensorFlow / Keras

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/RimshaKanwal0/customer-churn-prediction.git
   cd customer-churn-prediction
