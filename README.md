# Financial Client Attrition Forecasting System
## Author: Anesh Thangaraj
## Project Overview  
This project is designed to forecast the likelihood of financial clients discontinuing their relationship with a banking institution. By analyzing customer profiles, the model aims to proactively identify at-risk individuals. Client attrition poses a direct risk to revenue and operational continuity, making early prediction critical for financial organizations.

The project uses machine learning models to generate accurate churn predictions, allowing institutions to take proactive steps toward customer retention and long-term profitability.

---

## About the Dataset  
The dataset is sourced from Kaggle and comprises 10,000 rows and 14 columns. Each row represents a unique customer with demographic and financial information. The goal is to predict whether a customer will leave the institution based on these features.

---

## Key Features

**Independent Variables (Predictors):**
- **Demographics:**  
  - Age  
  - Gender  
  - Country of Residence (Geography)

- **Financial Metrics:**  
  - Credit Score  
  - Bank Balance  
  - Estimated Salary

- **Service & Interaction Details:**  
  - Number of Products Used  
  - Tenure with the Bank (in years)  
  - Active Membership Status  
  - Credit Card Ownership  

**Target Variable:**
- **Exited:**  
  Binary indicator showing if the customer exited the bank (1 = Yes, 0 = No)

---

## Data Dictionary

| Column Name       | Description                                                  |
|-------------------|--------------------------------------------------------------|
| RowNumber         | Row index in the dataset                                     |
| CustomerId        | Unique identifier for each customer                          |
| Surname           | Last name of the customer                                    |
| CreditScore       | Credit score of the customer                                 |
| Geography         | Customer’s country                                           |
| Age               | Age of the customer                                          |
| Tenure            | Years of relationship with the bank                          |
| Balance           | Account balance in USD                                       |
| NumOfProducts     | Number of bank products used by the customer                 |
| HasCrCard         | 1 if customer holds a credit card, 0 otherwise               |
| IsActiveMember    | 1 if customer is active, 0 otherwise                         |
| EstimatedSalary   | Annual estimated salary (USD)                                |
| Exited            | 1 if the customer churned, 0 if retained                     |

---

## Objective and Approach

**Objective:**  
To build a machine learning model that predicts client churn with high accuracy, helping the bank retain valuable customers.

**Approach:**  
- **Data Preprocessing:**  
  Cleaning data and addressing missing or inconsistent values.

- **Exploratory Data Analysis (EDA):**  
  Uncovering trends and identifying key variables impacting churn.

- **Feature Engineering:**  
  Enhancing or transforming features to boost model performance.

- **Modeling:**  
  Applying algorithms like Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.

- **Evaluation:**  
  Using metrics such as Accuracy, Precision, Recall, F1 Score, and ROC-AUC to assess model quality.

---

## Conclusion  
An effective churn prediction model empowers financial institutions to identify clients likely to leave and engage them with personalized retention strategies. This leads to improved client satisfaction, reduced attrition, and enhanced financial performance.

---

## About  
This project applies machine learning to forecast financial client behavior based on demographic and account-level features such as age, balance, credit score, product usage, and country of residence.

---

## Resources  
- `Readme`  
- `Jupyter Notebook` (Modeling and EDA)

---

## Languages  
- **Jupyter Notebook** – 100%

---
