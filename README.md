# 🏦 Credit Risk ML System – Probability of Default (PD) Model

## 📌 Overview

This project implements an end-to-end machine learning pipeline to predict the **Probability of Default (PD)** for loan applicants.

The goal is to simulate a production-aligned credit risk scoring system that can later integrate into a broader lending decision engine (e.g., mortgage or unsecured lending systems).

The solution is built using:

- Microsoft Azure Machine Learning
- Python (Scikit-learn)
- Risk-aware evaluation metrics
- Modular, reusable architecture

---

## 🎯 Business Objective

To estimate the likelihood that a borrower will default on a loan, enabling:

- Risk-based pricing  
- Credit approval decision support  
- Portfolio risk monitoring  
- Expected loss minimization  

This mirrors real-world credit risk modeling practices used in commercial banking environments.

---

## 🧠 Model Scope (MVP)

The Minimum Viable Product (MVP) includes:

- Binary classification (Default vs Non-default)
- Probability output between 0 and 1
- Baseline model: Logistic Regression
- Advanced model: Random Forest
- Evaluation metrics:
  - ROC-AUC
  - Precision
  - Recall
  - Confusion Matrix
- Threshold optimization for business-aligned decisions

---

## 📊 Dataset

The MVP version uses the **German Credit dataset** for rapid prototyping and structured experimentation.

Future versions may extend to larger, real-world datasets such as Home Credit Default Risk.

---

## 📈 Risk-Aware Evaluation Philosophy

Unlike typical ML projects that focus only on accuracy, this system evaluates performance from a **credit risk perspective**, including:

- Trade-off between approving risky clients vs rejecting good clients  
- Threshold tuning for business optimization  
- Model interpretability for regulatory alignment  

---

## 🔄 Future Enhancements

- Model calibration (Platt scaling / Isotonic regression)
- SHAP explainability
- Azure ML Model Registry integration
- REST API deployment
- Integration into Mortgage Risk Engine

---

## 👤 Author

Maxwell Zwane  
Azure ML | Data Engineering | Credit Risk Modeling  

---

## 🚀 Project Status

🟢 MVP Development Phase – In Progress
