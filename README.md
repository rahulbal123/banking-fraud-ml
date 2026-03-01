# 🏦 Production-Grade Banking Fraud Detection System

## 📌 Project Overview

This project demonstrates an end-to-end production-ready Machine Learning pipeline for detecting fraudulent banking transactions.

The solution includes:

- Multi-table synthetic banking data
- Data ingestion from CSV, JSON, XML, and PDF
- ETL validation and data quality checks
- Feature engineering
- Feature store simulation
- Imbalanced fraud handling
- XGBoost model training
- Model serialization
- Real-time inference simulation
- Drift detection
- Production issue handling

---

## 🏗 Architecture

Data Sources:
- Transactions (CSV)
- Customer Master (JSON)
- Device Intelligence (XML)
- KYC Risk (PDF)

Pipeline:
Data Ingestion → ETL Validation → Feature Engineering → Model Training → Model Registry → Inference → Monitoring

---

## 🛠 Tech Stack

- Python
- Pandas
- XGBoost
- Scikit-learn
- PyPDF2
- XML Parsing
- Parquet Feature Store Simulation
- Joblib
- Drift Detection (KS Test)

---

## 🚀 How to Run

1. Clone repository
2. Install requirements
3. Run notebook in Google Colab or Jupyter
