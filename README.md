# 📊 Bank Marketing Campaign Analysis & Fixed Deposit Prediction

A data analytics and machine learning project that predicts whether a bank customer is likely to subscribe to a fixed deposit product. The project combines exploratory data analysis (EDA) with predictive modeling to help the bank improve customer targeting, increase campaign efficiency, and reduce unnecessary marketing costs.

---

## 🎯 Business Problem

Banks spend significant time and resources contacting customers during marketing campaigns, but many customers are unlikely to subscribe to a fixed deposit. This project aims to identify the characteristics of customers who are more likely to subscribe and build a predictive model that supports more effective marketing decisions.

---

## 📌 Project Objectives

- Analyze customer demographics, financial characteristics, and marketing campaign data.
- Identify factors associated with fixed deposit subscription.
- Develop and compare multiple machine learning classification models.
- Select the best-performing model for predicting customer subscription.
- Provide business recommendations to improve future marketing campaigns.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Jupyter Notebook**

---

## 📂 Dataset

The project uses the **Bank Marketing Dataset**, which contains customer demographic information, financial details, and historical marketing campaign data from a Portuguese banking institution.

**Target Variable:** `deposit` (Yes / No)

---

## 📊 Exploratory Data Analysis

The analysis examined:

- Customer occupation
- Marital status
- Education level
- Housing and personal loans
- Account balance
- Contact method
- Previous campaign outcomes
- Numerical variables such as age, campaign contacts, and previous interactions

### Key Insights

- **Students and retired customers** recorded the highest subscription rates.
- Customers with **tertiary education** were more likely to subscribe.
- Customers **without housing or personal loans** showed higher subscription rates.
- **Previous campaign success** was one of the strongest predictors of future subscription.
- Customers contacted through **cellular channels** responded more positively than those contacted through other methods.

---

## 🤖 Machine Learning Models

The following models were evaluated:

| Model | Accuracy |
|------|----------:|
| Logistic Regression | 71.34% |
| Decision Tree | 67.80% |
| Random Forest | 73.44% |
| **XGBoost** | **74.21%** |

### 🏆 Best Model

**XGBoost** achieved the highest predictive performance and was selected as the final model.

---

## 📈 Feature Importance

The most influential features included:

- Account Balance
- Age
- Previous Campaign Success (`poutcome_success`)
- Number of Campaign Contacts
- Previous Customer Interactions (`previous`, `pdays`)

These findings indicate that customer financial capacity and historical marketing engagement play a major role in predicting fixed deposit subscription.

---

## 💡 Business Recommendations

- Prioritize customers with successful previous campaign outcomes.
- Use predictive analytics for customer targeting.
- Optimize communication channels (especially cellular).
- Incorporate financial characteristics into customer segmentation.
- Retrain the model periodically using recent campaign data.

---

## 📁 Project Structure

```text
Bank-Marketing-Prediction/
│
├── data/
│   └── bank.csv
│
├── notebooks/
│   └── bank_marketing_analysis.ipynb
│
├── reports/
│   └── bank_marketing_report.pdf
│
├── images/
│   ├── target_distribution.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
└── README.md
```

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/yourusername/Bank-Marketing-Prediction.git

# Navigate into the project folder
cd Bank-Marketing-Prediction

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

---

## 📄 Project Report

📥 **[Download the full project report (PDF)](reports/bank_marketing_report.pdf)**

---

## 🔗 Connect With Me

**Okunbor Promise**

- LinkedIn: https://www.linkedin.com/in/your-linkedin
- GitHub: https://github.com/yourusername
- Email: your.email@example.com

---

⭐ If you found this project useful, feel free to **star the repository** and connect with me on LinkedIn.
