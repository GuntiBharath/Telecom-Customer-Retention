# 📞 Telecom Customer Retention – Churn Prediction with ML

This project aims to predict customer churn for a telecom company using machine learning. It analyzes customer behavior, usage patterns, and account information to identify customers likely to leave. The goal is to help businesses improve customer retention and reduce revenue loss.

---

## 📊 Dataset

- **Source:** TelecomCustomerChurn.csv  
- **Attributes include:**  
  - Demographics (gender, senior citizen, etc.)  
  - Service details (internet service, phone line, etc.)  
  - Account information (contract type, monthly charges, etc.)  
  - Churn status (Yes/No)

---

## 🔍 Project Workflow

1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Model Building** (Random Forest, XGBoost, Logistic Regression)
5. **Model Evaluation** using metrics like accuracy, precision, recall, F1-score, and ROC-AUC
6. **Result Interpretation** through feature importance
7. *(Optional)* Deployment using Streamlit or Flask

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- google colab

---

## 📈 Results

- **Best Model:** Random Forest  
- **ROC AUC Score:** 0.83  
- **Accuracy:** ~85%  
- **Key Influencing Features:**
  - Contract Type
  - Tenure
  - Monthly Charges
