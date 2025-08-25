# 🏦 Loan Default Risk Prediction 

This project focuses on predicting **loan default risk** using historical financial data and customer demographics. The main objective is to build a reliable machine learning model to identify potential borrowers who are at higher risk of defaulting on their loans.

---

## 📌 Project Overview

Financial institutions often face challenges in minimizing **non-performing loans** while still offering competitive credit options.
By leveraging **machine learning**, this project develops a predictive model that helps assess the **probability of loan default** based on key customer and financial features.

---

## 📂 Dataset

* **Source:** Internal financial dataset
* **Total Records:** \~300,000+ loan applications
* **Target Variable:** `loan_status` → 1 = Default, 0 = Non-default
* **Key Features:**

  * `GENDER_MAP` → Borrower's gender
  * `EXT_SOURCE_2` & `EXT_SOURCE_3` → External credit scoring
  * `DAYS_BIRTH` → Borrower’s age
  * Other financial & demographic variables

---

## 🧠 Modeling

Several machine learning models were evaluated, including:

| Model                    | Accuracy | ROC-AUC  |
| ------------------------ | -------- | -------- |
| Logistic Regression      | 71%      | 0.76     |
| Decision Tree            | 69%      | 0.72     |
| Random Forest            | 74%      | 0.80     |
| **XGBoost (Best Model)** | **78%**  | **0.85** |

The **XGBoost model** was selected as the best-performing classifier based on overall predictive accuracy and AUC score.

---

## 🔍 Feature Importance

The top 3 most influential features from the XGBoost model are:

| Rank | Feature Name   | Impact on Prediction |
| ---- | -------------- | -------------------- |
| 1    | `EXT_SOURCE_2` | High influence       |
| 2    | `EXT_SOURCE_3` | High influence       |
| 3    | `DAYS_BIRTH`   | Moderate influence   |
| 4    | `GENDER_MAP`   | Moderate influence   |

---

## 💡 Business Recommendations

Based on the **feature importance** analysis, the following strategic actions are recommended:

### **1. Gender-Based Loan Programs** *(GENDER\_MAP)*

Design tailored loan programs that match customer needs and repayment tendencies based on gender. This personalization can improve loan approval quality and repayment rates.

---

### **2. Enhanced Credit Scoring** *(EXT\_SOURCE\_2 & EXT\_SOURCE\_3)*

Leverage additional external data sources, such as:

* Telephone bill payment history
* Rental payment records
* Other credit histories from external institutions
  This approach can strengthen the creditworthiness assessment process.

---

### **3. Age-Specific Loan Policies** *(DAYS\_BIRTH)*

Develop age-specific loan products, possibly with restrictions for certain age groups to reduce high-risk lending.

---

## 📊 Business Impact

Implementing this model can help:

* Reduce **loan default rates** 
* Improve **credit approval accuracy**
* Enable **data-driven decision-making** for financial institutions

---

## 📎 Repository Structure

```
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks for EDA & modeling
├── src/                 # Model scripts & pipeline
├── reports/             # Results & visualizations
└── README.md            # Project documentation
```

---

## 🚀 How to Use

```bash
# Clone repository
git clone https://github.com/username/loan-default-risk.git

# Install dependencies
pip install -r requirements.txt

# Run the model
python src/train_model.py
```

---

## 📧 Contact

For questions or collaborations:
**Hanifah Arrasyidah**
📩 [hanifaharrasyiah@gmail.com](mailto:hanifaharrasyiah@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/hanifaharrasyiah)

