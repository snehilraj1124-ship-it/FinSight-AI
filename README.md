# 💳 FinSight AI

### Intelligent Financial Risk & Fraud Detection Platform

FinSight AI is an end-to-end machine learning platform designed to analyze financial transactions, detect potentially fraudulent activity, assess credit risk, and generate actionable risk scores.

The project combines **Machine Learning, Python, Data Analytics, Feature Engineering, Streamlit, and Flask REST API** into a single financial risk analytics solution.

---

## 🚀 Key Features

- 🔍 Financial transaction fraud detection
- 📊 Exploratory data analysis and risk analytics
- 🤖 Machine learning-based fraud classification
- 💰 Credit risk assessment
- 📈 Transaction risk scoring
- ⚙️ Automated APPROVE / REVIEW decision support
- 📊 Interactive Streamlit dashboard
- 🌐 Flask REST API for transaction scoring
- 🧠 Feature engineering for financial risk indicators
- 📋 Model performance evaluation
- 💾 Saved trained ML models

---

## 🏗️ System Architecture

```text
Financial Transactions
          ↓
   Data Validation
          ↓
   Feature Engineering
          ↓
 ┌────────┴─────────┐
 ↓                  ↓
Fraud Detection   Credit Risk
   Model             Model
 ↓                  ↓
Fraud Probability  Risk Probability
 └────────┬─────────┘
          ↓
   Overall Risk Score
          ↓
   Business Decision
     APPROVE / REVIEW
          ↓
 Dashboard / REST API
