## 📌 Business Problem
Predicting customer churn is critical for telecom companies to retain customers and reduce revenue loss. This project develops a machine learning model to identify customers likely to churn based on their demographic and service usage patterns.

## 📁 Dataset Story
- **Source:** Telco Customer Churn Dataset
- **Records:** 7,043 customers
- **Features:** 21 variables including demographic info, services subscribed, account details
- **Target:** Churn (Yes/No) 

## 🧮 Exploratory Data Analysis (EDA)
Key insights from data exploration:
- 26.6% overall churn rate
- Significant correlations between churn and:
  - Contract type (Month-to-month vs Longer terms)
  - Internet service type
  - Payment method
  - Tenure duration
 
## ⚙️ Feature Engineering
Created new features to improve model performance:
- Tenure-based year categories
- Service bundling features
- Encoded categorical variables
- Scaled numerical features

## 🤖 Machine Learning Model
- **Logistic Regression**

## ⚖️ Handling Imbalanced Data
- **Manual Undersampling**

### Results:
- **Recall improvement:** 55% → 84% for churn class
- **F1-score improvement:** 61% → 64% for churn class
- **Accuracy:** 81% → 75% (acceptable trade-off for business needs)

### Most Important Features
-Contract_Two year - 2-year contracts significantly reduce churn risk
-NEW_Engaged_1 - Engaged customers show lower churn rates
-InternetService_Fiber optic - Fiber optic users have higher churn probability
-NEW_Increase - Recent price increases correlate with churn
-tenure - Longer customer lifetime reduces churn risk

