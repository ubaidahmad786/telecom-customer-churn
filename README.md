# Telecom Customer Churn Prediction

A Machine Learning project focused on predicting whether a customer will leave a telecom provider. This solution helps businesses identify high-risk customers and implement proactive retention strategies using predictive modeling.

## 🚀 Features
* **Exploratory Data Analysis (EDA):** Visualized customer demographics, tenure distribution, and contract types using Seaborn and Matplotlib.
* **Class Imbalance Handling:** Implemented **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the churn vs. non-churn classes.
* **Feature Engineering:** Handled categorical variables using `LabelEncoder` and prepared data for robust modeling.
* **Predictive Modeling:** Trained and evaluated classification models including **Decision Trees** and **Random Forests** using Scikit-Learn.
* **Performance Evaluation:** Analyzed models using Confusion Matrices and Classification Reports (Precision, Recall, F1-Score).

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning Libraries:** Scikit-Learn, Imbalanced-learn (SMOTE)
* **Data Analysis & Visualization:** Pandas, NumPy, Matplotlib, Seaborn

## 📈 Key Insights & Results
* **Imbalance Resolution:** Addressed target class skewness effectively using SMOTE to ensure the model doesn't over-rely on majority class characteristics.
* **Model Choice:** The Random Forest Classifier achieved stable performance across precision and recall metrics.

## 🔧 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/ubaidahmad786/telecom-customer-churn.git](https://github.com/ubaidahmad786/telecom-customer-churn.git)
