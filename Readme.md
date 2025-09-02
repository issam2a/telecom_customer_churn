# 📞 Telecom Customer Churn Prediction

This project aims to analyze telecom customer data to predict churn (whether a customer will leave the company). Using machine learning and data analysis techniques, we explore customer behavior patterns and train a classification model to help the business take proactive retention measures.

---

## 📊 Project Overview

- **Objective**: Predict if a telecom customer will churn based on their service usage and account information.
- **Tech Stack**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook
- **ML Algorithms Used**: Logistic Regression.
- **Dataset**: Public telecom churn dataset containing features like customer demographics, service subscriptions, and billing info.

---

## 📁 Dataset Description

The dataset includes the following columns:

| Column | Description |
| --- | --- |
| `customerID` | Unique customer identifier |
| `Gender` | Male or Female |
| `SeniorCitizen` | 1 if senior citizen, 0 otherwise |
| `Partner` | Has a partner or not |
| `Dependents` | Has dependents or not |
| `Tenure` | Number of months as a customer |
| `PhoneService` | Has phone service or not |
| `MultipleLines` | Has multiple lines or not |
| `InternetService` | Type of internet service |
| `OnlineSecurity` | Has online security or not |
| `OnlineBackup` | Has online backup or not |
| `DeviceProtection` | Has device protection or not |
| `TechSupport` | Has tech support or not |
| `StreamingTV` | Has streaming TV or not |
| `StreamingMovies` | Has streaming movies or not |
| `Contract` | Type of contract (Month-to-month, One year, Two year) |
| `PaperlessBilling` | Whether billing is paperless |
| `PaymentMethod` | Payment method used |
| `MonthlyCharges` | Monthly billing amount |
| `TotalCharges` | Total billing amount |
| `Churn` | Target variable (Yes or No) |

---

## 🧪 Project Steps

1. **Data Loading & Cleaning**
    - Handle missing values
    - Convert data types
    - Encode categorical variables
2. **Exploratory Data Analysis (EDA)**
    - Univariate and bivariate analysis
    - Visualizing churn trends and correlations
3. **Feature Engineering**
    - Encoding
    - Scaling numeric features
    - Handling class imbalance if needed
4. **Model Building**
    - Train/test split
    - Try multiple classifiers (Logistic Regression, Random Forest, etc.)
    - Hyperparameter tuning (GridSearchCV)
5. **Model Evaluation**
    - Confusion Matrix
    - Accuracy, Precision, Recall, F1-score
    - ROC-AUC Curve
6. **Insights & Recommendations**
    - Key churn drivers
    - Actionable suggestions for customer retention

---

## 📌 Installation & Requirements

Install dependencies using pip:

```bash
pip install -r requirements.txt
```

Make sure you have Python 3.7+ and Jupyter Notebook installed.

## 📈 Example Results

- **Best Model**: Random Forest
- **Accuracy**: ~82%
- **Top Features Influencing Churn**:
    - Contract Type
    - Tenure
    - Monthly Charges
    - Online Security

## 🤖 Future Work

- Deploy the model as a web API using Flask or FastAPI
- Implement a dashboard for visualizing churn metrics
- Test on real-time streaming data

---

## 👤 Author

- **Name**: Issam Issa
- **LinkedIn**: 🌐[www.linkedin.com/in/issam-issa](http://www.linkedin.com/in/issam-issa)
- **GitHub**:https://github.com/issam2a/telecom_customer_churn.git
- **Email**: [Issamissa2a@gmail.com](mailto:Issamissa2a@gmail.com)