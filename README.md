# 💳 Financial Client Attrition Forecasting System  
**Author:** Anesh Thangaraj  
**Institution:** The George Washington University – MS in Business Analytics  
 
---

## 📘 Overview  
This project addresses customer attrition challenges in the banking sector by:

- Predicting which clients are likely to leave the bank (churn)
- Comparing multiple supervised machine learning models
- Using model results to guide proactive client retention strategies

The forecasting is based on structured demographic and financial data, and the goal is to reduce revenue loss by accurately identifying at-risk clients.

---

## 🔍 Business Objective  
To enhance customer retention efforts by:

- Forecasting churn probability with high accuracy  
- Informing marketing, outreach, and retention strategies with model-driven insights  

---

## 🧠 Modeling Approach  

**Data:**  
- Source: Public dataset (10,000 records)  
- Data type: Structured, customer-level data  
- Features: Demographics + Financial Metrics + Service Interactions  

**Feature Engineering:**  
- One-hot encoding for categorical variables (e.g., geography, gender)  
- Standardization for continuous variables  
- Derived features: tenure bucket, customer engagement score  

---

## 🤖 Models Compared  

| Model               | Accuracy | Precision | Recall | ROC-AUC |
|--------------------|----------|-----------|--------|---------|
| Logistic Regression| 81.5%    | 79.4%     | 74.3%  | 0.84    |
| Decision Tree      | 79.2%    | 75.1%     | 72.0%  | 0.81    |
| Random Forest      | 84.3%    | 82.1%     | 78.7%  | 0.87    |
| Gradient Boosting  | 85.1%    | 83.2%     | 79.6%  | 0.88    |
| K-Nearest Neighbors| 76.4%    | 71.3%     | 68.9%  | 0.78    |
| Neural Network     | 83.6%    | 80.5%     | 76.1%  | 0.86    |

---

## 🏆 Insights & Recommendation  

- **Gradient Boosting** delivered the best overall performance (highest ROC-AUC + solid accuracy).  
- **Logistic Regression** remains a reliable and interpretable baseline.  
- Ensemble models significantly outperformed simpler classifiers on this dataset.  
- Churners typically had **lower tenure**, **fewer products**, and were **less active**.  

---

## 🛠 Implementation Tips  

- Deploy the Gradient Boosting model in CRM systems  
- Prioritize high-risk clients for retention campaigns  
- Monitor key churn indicators: inactivity, low product use, declining balances  
- Retrain the model quarterly with updated transaction and behavioral data  

---

## ⚠️ Limitations  

- Historical data only—no transactional or behavioral trends over time  
- No feedback loop from actual retention efforts (no intervention data)  
- Cost of misclassification not integrated into the model (business proxy needed)  

---

## 🚀 Future Scope  

- Incorporate time-series trends or customer activity logs  
- Use SHAP for interpretable churn factors per individual  
- Integrate with financial call center logs or CRM interaction histories  
- Extend to multi-class models (e.g., high, medium, low churn risk)  

---

## 📬 Contact  

**Anesh Thangaraj**  
✉️ aneshraj14@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile)
