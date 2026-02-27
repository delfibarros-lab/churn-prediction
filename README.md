# 📉 Customer Churn Prediction - End-to-End Classification

## 📋 Context & Objective
Customer retention is more cost-effective than customer acquisition. This project is an end-to-end Machine Learning classification pipeline designed to predict whether a customer will cancel their telecommunications service (Churn).
The goal is to demonstrate a complete data science workflow: from data preprocessing and feature engineering to model training, comparison, and evaluation using industry-standard metrics.

## 🛠️ Tools & Technologies
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn (Logistic Regression, Random Forest)
- **Data Visualization:** Seaborn, Matplotlib
- **Environment:** Google Colab

## 🚀 Methodology
1. **Data Preprocessing:** Handled missing values (e.g., converting blank strings to numerical values in billing data) and removed unnecessary columns.
2. **Feature Engineering:** Converted categorical variables into numerical format using One-Hot Encoding (`pd.get_dummies`).
3. **Scaling & Splitting:** Standardized numerical features and split the dataset into training (80%) and testing (20%) sets.
4. **Model Training:** Trained and compared a baseline Logistic Regression model against a Random Forest Classifier.
5. **Evaluation:** Assessed model performance using precision, recall, F1-score, and the ROC-AUC score to account for class imbalances.

## 💡 Executive Conclusions
- **Tenure & Contracts:** Customers with month-to-month contracts and short tenure are at the highest risk of churning.
- **Model Performance:** The Random Forest model successfully identified at-risk customers, but Logistic Regression provided better interpretability for the business team.
- **Business Action:** The company should offer targeted incentives (e.g., discounted yearly contracts) to customers flagged by the model as high-risk within their first 6 months.
