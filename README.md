<h1 align="center">Hi, I'm Mohamed Kamal 👋</h1>

<p align="center">
  <b>ML Engineer · Data Engineer</b><br>
  Building production-ready AI systems and data pipelines — Amsterdam, Netherlands 🇳🇱
</p>

<p align="center">
  <a href="mailto:mohamedkamal.ams@gmail.com">mohamedkamal.ams@gmail.com</a> ·
  <a href="https://linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a>
</p>

---

## About Me

I'm a machine learning and data engineer focused on building end-to-end systems — from raw data to deployed models to production pipelines. I care about rigorous evaluation, honest documentation, and work that holds up in the real world.

With a background spanning ML modelling, stream processing, and API design, I work across the full lifecycle: ingest, validate, train, serve, monitor. I'm currently based in Amsterdam and open to ML engineering and data engineering roles.

---

## Featured Projects

### 🫀 EarlyPulse — Early Sepsis Detection System
> XGBoost · GRU · FastAPI · Streamlit · Docker · SHAP · Optuna · PhysioNet 2019

ML system for early sepsis detection applied to 20,317 real ICU patients. XGBoost model achieves **AUROC 0.9514** and **AUPRC 0.7622** on a held-out patient-level test set — above published clinical baselines. Includes SHAP explainability, Brier score calibration, Optuna hyperparameter tuning (60-trial sweep), automated drift monitoring, a deployed FastAPI REST endpoint, and a live Streamlit dashboard.

- Patient-level train/test split to prevent data leakage
- Drift monitoring via KS-test and Population Stability Index across all 37 features
- Top features: Lactate, Heart Rate, Respiratory Rate, BUN, Creatinine — clinically validated

🔗 [GitHub](https://github.com/kamal-01-wjua/EarlyPulse) · [Live Demo](https://earlypulse-n9gi6hrif9a3m8yw8skm23.streamlit.app)

---

### ⚡ SafeFlow — Hybrid Streaming & Batch Risk Pipeline
> Redpanda · Faust · PostgreSQL 16 · FastAPI · Next.js · Docker · GitHub Actions · Redis

Production-grade financial risk scoring pipeline processing **10,000+ events at 5,285 msg/s** with ~20ms stream latency. Covers the full data engineering lifecycle: event ingestion, Pydantic validation (7 rejection codes), idempotent upserts, streaming feature store, daily batch recompute, JWT-secured REST API, and an analyst-facing Next.js dashboard.

- Lambda architecture: streaming approximation + batch accuracy layer
- 76 unit tests · 3/3 CI jobs passing (pytest, ruff, Docker build)
- Honest scoping: built components documented separately from stubs and planned work

🔗 [GitHub](https://github.com/kamal-01-wjua/safeflow)

---

## Tech Stack

**Languages:** Python · SQL · JavaScript  
**ML & Data:** XGBoost · PyTorch (GRU) · scikit-learn · pandas · SHAP · Optuna · Plotly · Seaborn  
**Data Engineering:** Redpanda · Faust · PostgreSQL · Redis · SQLModel · Pydantic  
**APIs & Backend:** FastAPI · Docker · GitHub Actions  
**Dashboards:** Streamlit · Next.js · Power BI · Tableau  

---

## Certifications

- 📊 Google Data Analytics Professional Certificate — Google
- 🤖 Machine Learning Specialization — DeepLearning.AI & Stanford Online

---

## Currently

- 📍 Based in Amsterdam, open to ML Engineering and Data Engineering roles
- 🔭 Building and extending EarlyPulse and SafeFlow
- 📬 Reach me at [mohamedkamal.ams@gmail.com](mailto:mohamedkamal.ams@gmail.com)
