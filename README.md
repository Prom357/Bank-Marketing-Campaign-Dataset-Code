# Bank Marketing Campaign Prediction using Machine Learning

## Project Overview
This project predicts whether a customer will subscribe to a **fixed deposit** using machine learning techniques. The goal is to help banks identify customers who are most likely to subscribe before launching future marketing campaigns, improving campaign efficiency and reducing unnecessary marketing costs.

---

## Business Problem
Banks spend significant resources contacting customers during direct marketing campaigns, but many customers are not interested in the product. The objective of this project is to use historical customer and campaign data to identify high-potential customers and improve marketing effectiveness.

---

## Dataset
The project uses the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

- **Records:** 11,162
- **Variables:** 17
- **Target Variable:** `deposit` (Yes / No)

The dataset contains:
- Customer demographic information
- Financial characteristics
- Current campaign information
- Previous campaign outcomes

---

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Project Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development
5. Model Evaluation
6. Business Recommendations

---

## Exploratory Data Analysis
Key findings from the analysis:

- Customers with successful previous campaign outcomes were much more likely to subscribe again.
- Cellular communication channels recorded the highest subscription rates.
- Customers without housing or personal loans showed higher subscription rates.
- Campaign month influenced customer response, suggesting possible seasonal patterns.

---

## Models Evaluated

| Model | Accuracy |
|---|---:|
| Logistic Regression | 71.34% |
| Decision Tree | 67.80% |
| Random Forest | 73.44% |
| **XGBoost** | **74.21%** |

---

## Final Model
**XGBoost** achieved the highest predictive performance and was selected as the final model. Feature importance analysis showed that previous campaign success, communication channel, campaign timing, and customer loan status were among the most influential predictors of subscription.

---

## Business Recommendations
- Prioritize customers who responded positively in previous campaigns.
- Use mobile communication as the primary contact channel.
- Apply the XGBoost model for customer targeting.
- Use loan status as part of customer segmentation.
- Monitor and update the model regularly using recent campaign data.

---


## Files Included
- **Bank_Marketing_Campaign_Prediction_Report.pdf** — Full project report
- **Code (bank_marketing_analysis.ipynb)** — Jupyter Notebook containing the analysis and model development
- **bank.csv** — Dataset used for the project

---

## Key Business Impact
By using the XGBoost model, the bank can:

- Improve customer targeting
- Increase campaign efficiency
- Reduce unnecessary marketing costs
- Make more effective data-driven marketing decisions

---

## Author
**Okunbor Promise**  
Data Analyst Portfolio Project

- LinkedIn: https://www.linkedin.com/in/promise-okunbor-32926b160/edit/intro/
