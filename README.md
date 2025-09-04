# 💳 Credit Card Fraud Detection  

## 🚨 Problem Statement  
Credit card fraud detection is one of the most critical challenges in the banking and financial industry. The goal of this project is to build machine learning models that can distinguish between **fraudulent** and **legitimate** transactions.  

We work with a real-world dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains **2,84,807 transactions** carried out by European cardholders over two days in 2013. Out of these, only **492 transactions are fraudulent** (≈0.17%), making this a **highly imbalanced dataset**.  

---

## 💼 Business Context  
Banking fraud poses a massive risk, costing institutions billions of dollars each year while eroding customer trust. According to the [Nilson Report](https://nilsonreport.com/upload/content_promo/The_Nilson_Report_Issue_1164.pdf), global card fraud losses were estimated to reach **$30 billion by 2020**.  

With the surge in online payments, fraudsters constantly develop new techniques. Hence, **fraud detection using machine learning** is not just beneficial but essential. It enables:  
- ⏱ Faster and automated fraud detection  
- 💸 Reduced losses from chargebacks and penalties  
- 🙌 Improved customer confidence in digital payments  

---

## 🔎 Understanding Fraud  
Fraud can take multiple forms, including:  
- Skimming (duplicating data from a card’s magnetic strip)  
- Alteration or manipulation of genuine cards  
- Creation of counterfeit cards  
- Usage of stolen or lost cards  
- Fraudulent telemarketing schemes  

---

## 📊 Dataset Overview  
- **Transactions:** 2,84,807  
- **Fraudulent:** 492 (0.172%)  
- **Legitimate:** 2,84,315  
- **Features:**  
  - `Time`: Seconds elapsed between the first and the current transaction  
  - `Amount`: Transaction amount  
  - `V1 … V28`: PCA-transformed features (for confidentiality)  
  - `Class`: Target variable → `1` for fraud, `0` for non-fraud  

---

## 🛠 Project Pipeline  
1. **Data Understanding** → Load and explore features  
2. **Exploratory Data Analysis (EDA)** → Analyze distributions, detect patterns, handle skewness  
3. **Data Splitting & Sampling** → Train/test split and k-fold cross-validation to handle imbalance  
4. **Model Building & Tuning** → Train multiple ML models, optimize hyperparameters  
5. **Evaluation** → Focus on metrics like **Precision, Recall, F1-score, and AUC-ROC**, since accuracy alone is misleading in imbalanced datasets  

---

## 🎯 Key Takeaways  
- Imbalanced datasets require **special handling** (resampling, anomaly detection, cost-sensitive learning).  
- Models should prioritize **catching fraudulent cases** even if it means a small increase in false positives.  
- Precision, Recall, and F1-score provide a much better reflection of business goals than raw accuracy.  

---

## 📌 Tech Stack  
- **Languages**: Python 🐍  
- **Libraries**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **ML Techniques**: Logistic Regression, Decision Trees, Random Forest, XGBoost, Resampling Methods (SMOTE/Under-sampling)  

---

✨ This project demonstrates how machine learning can empower banks to build proactive fraud detection systems that safeguard customers and minimize financial risks.  
