# Startup Failure Intelligence & Prediction Platform

An AI-powered startup intelligence system that predicts startup failure risk, identifies key risk factors, benchmarks startup health across categories and geographies, and evolves toward simulation and business-advisory capabilities.

---

## 1. Overview

Startup ecosystems are highly uncertain. Many startups raise funding, operate for a few years, and then either shut down, get acquired, or continue operating with varying levels of health. Investors, founders, and analysts often struggle to answer questions such as:

* Which startups are at high risk of failure?
* Which funding patterns indicate stronger survival potential?
* How healthy is a startup compared to similar startups in its category or geography?
* What factors are most responsible for startup risk?

This project aims to build a **Startup Failure Intelligence & Prediction Platform** that goes beyond a simple classifier and moves toward a decision-support system for startup risk analysis.

---

## 2. Problem Statement

Most beginner startup prediction projects stop at a binary success/failure classifier. However, startup outcomes are influenced by multiple signals such as funding behavior, startup age, category, and geography.

This project is designed to answer not only **whether a startup is risky**, but also:

* **why** it is risky,
* **how healthy** it is compared to similar startups,
* and **what factors** may improve or worsen its survival outlook.

---

## 3. Objectives

The key objectives of this project are:

* Predict startup failure / closure risk using startup metadata and funding history
* Build a startup health score based on funding, age, and category/geography signals
* Detect major risk factors behind startup failure predictions
* Provide explainable AI outputs for model predictions
* Benchmark startups by industry/category and geography
* Lay the foundation for advanced modules such as what-if simulation, survival forecasting, and AI business recommendations

---

## 4. Dataset

### Current Base Dataset

**Dataset:** `big_startup_secsees_dataset.csv`

### Available Columns

* `permalink`
* `name`
* `homepage_url`
* `category_list`
* `funding_total_usd`
* `status`
* `country_code`
* `state_code`
* `region`
* `city`
* `funding_rounds`
* `founded_at`
* `first_funding_at`
* `last_funding_at`

### Dataset Notes

This dataset provides startup-level metadata, funding history, category information, location information, and operating status. It is suitable for building a strong MVP around startup failure risk and startup health, but some advanced modules (such as founder readiness) will require later dataset enrichment or proxy features.

---

## 5. Project Scope

### Current MVP Scope

The first version of the platform focuses on the following:

* Startup failure / closure risk prediction
* Startup health score
* Funding-based and time-based risk factor analysis
* Explainable AI for predictions
* Category benchmarking
* Geography benchmarking
* Interactive dashboard (planned)

### Planned Advanced Features

The long-term platform vision includes:

* Success / outcome intelligence
* Founder Readiness Index
* What-If Simulator
* Survival Timeline Predictor
* AI Business Advisor
* Interactive dashboard with scenario analysis

---

## 6. Feature Engineering Plan

Since the raw dataset is limited, feature engineering plays a major role in the project.

### Planned Derived Features

#### Time-Based Features

* `startup_age_years`
* `time_to_first_funding`
* `funding_active_years`
* `years_since_last_funding`

#### Funding Features

* `avg_funding_per_round`
* `has_multiple_rounds`
* `high_funding_flag`
* `funding_recency_score`

#### Category Features

* `primary_category`
* `category_failure_rate`
* `category_median_funding`

#### Geography Features

* `country_failure_rate`
* `region_failure_rate`

---

## 7. Expected Workflow

The project workflow is designed as a multi-stage pipeline:

1. **Dataset audit and cleaning**
2. **Target variable design**
3. **Feature engineering**
4. **Exploratory data analysis**
5. **Model training and evaluation**
6. **Risk factor interpretation / explainability**
7. **Startup health score generation**
8. **Dashboard development**
9. **Advanced simulation and advisory modules**

---

## 8. Tech Stack

### Programming & Analysis

* Python
* Pandas
* NumPy

### Machine Learning

* Scikit-learn
* XGBoost / Gradient Boosting (if needed)

### Visualization

* Matplotlib
* Seaborn
* Plotly

### Explainability

* SHAP
* Feature importance analysis

### Dashboard

* Streamlit

---

## 9. Project Structure

```bash
Startup-Failure-Intelligence-Platform/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_dataset_audit.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_model_training.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── features.py
│   ├── train.py
│   ├── predict.py
│   └── scoring.py
│
├── dashboard/
│   └── app.py
│
├── models/
├── reports/
└── README.md
```

---

## 10. Current Status

### Completed

* Project vision finalized
* Long-term feature roadmap locked
* Base dataset selected
* Front-page / project charter prepared

### In Progress

* Dataset audit
* Target variable design
* Feature engineering planning

---

## 11. Future Roadmap

### Phase 1 — MVP

* Failure prediction
* Startup health score
* Risk factor detection
* Explainable AI
* Category and geography benchmarking

### Phase 2 — Enrichment

* Better outcome modeling
* Founder-related proxy features
* Stronger health scoring
* More robust business intelligence features

### Phase 3 — Advanced Intelligence Layer

* What-If Simulator
* Survival Timeline Predictor
* AI Business Advisor
* Interactive dashboard with richer scenario analysis

---

## 12. Why This Project Matters

This project is not intended to be just a toy “startup success prediction” classifier. The goal is to build a **startup intelligence platform** that demonstrates:

* business problem framing
* machine learning on imperfect real-world startup data
* feature engineering from funding and temporal signals
* explainable AI
* benchmarking and decision-support thinking
* product-oriented project design

---

## 13. Planned Output

By the end of the project, the platform is expected to provide:

* Startup risk prediction
* Startup health score
* Risk factor explanation
* Category / geography benchmarking
* Explainable AI outputs
* Interactive dashboard
* A roadmap toward simulation and business-advisory modules

---

## 14. Project Positioning

**Startup Failure Intelligence & Prediction Platform** can be positioned as:

> An AI-powered startup risk intelligence system that predicts startup failure, explains risk factors, benchmarks startup health, and evolves toward simulation and business-advisory capabilities.
