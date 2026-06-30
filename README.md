# 🚀 Startup Failure Intelligence & Prediction Platform

> An AI-powered platform to analyze startup data, identify failure patterns, predict startup outcomes, and provide explainable insights for founders, investors, and researchers.


# Project Overview

Startup failure is a major challenge worldwide. Many startups fail due to financial issues, market mismatch, poor timing, and operational problems. This project aims to build a machine learning platform that analyzes startup data, predicts startup outcomes, and explains the factors influencing those predictions.

The project follows a complete end-to-end Data Science pipeline, from data exploration and preprocessing to model development, explainable AI, and deployment.


# Project Objectives

- Analyze startup data using Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Engineer meaningful features
- Build machine learning models for startup outcome prediction
- Explain model predictions using Explainable AI (SHAP)
- Develop a Startup Health Score
- Build an interactive dashboard for visualization and prediction


# Dataset

**Dataset:** `big_startup_success_dataset.csv`

This project uses a Crunchbase-style startup dataset containing startup information such as:

- Startup Name
- Company Permalink
- Homepage URL
- Category List
- Country, State, Region, and City
- Funding Total (USD)
- Funding Rounds
- Founded Date
- First Funding Date
- Last Funding Date
- Startup Status

The dataset is used to understand startup characteristics, funding trends, and factors related to startup success or failure.


# Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Data Analysis | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn, XGBoost |
| Explainable AI | SHAP |
| Dashboard | Streamlit |
| Version Control | Git, GitHub |


# Project Structure

Startup-Failure-Intelligence/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_project_setup.ipynb
│   ├── 02_dataset_understanding.ipynb
│   ├── 03_initial_data_exploration.ipynb
│
├── src/
│
├── models/
│
├── reports/
│
├── dashboard/
│
├── requirements.txt
│
└── README.md

# Project Progress

| Day | Task | Status |
|------|-----------------------------------------------|-----------|
| Day 01 | Project Setup | ✅ Completed |
| Day 02 | Dataset Understanding | ✅ Completed |
| Day 03 | Initial Data Exploration & Data Quality Assessment | ✅ Completed |
| Day 04 | Data Cleaning & Preprocessing | ⏳ In Progress |


# Day-03 Summary

Completed the initial exploratory analysis of the dataset.

### Tasks Performed

- Imported required libraries
- Loaded the dataset
- Converted date columns into datetime format
- Extracted year-based features
- Analyzed dataset structure
- Checked missing values
- Calculated missing value percentage
- Identified duplicate records
- Analyzed unique values
- Generated statistical summary
- Investigated the `funding_total_usd` column for preprocessing


# Current Project Phase

**Exploratory Data Analysis (EDA)**

Current progress includes:

- Dataset Understanding
- Dataset Structure Analysis
- Missing Value Analysis
- Duplicate Detection
- Unique Value Analysis
- Statistical Summary
- Initial Feature Investigation


# Upcoming Work

- Data Cleaning
- Handling Missing Values
- Outlier Detection
- Feature Engineering
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Machine Learning Model Development
- Model Evaluation
- Explainable AI
- Dashboard Development
- Deployment

---

# Current Status

Day-03 Completed

The dataset has been explored successfully and is now ready for preprocessing and feature engineering.


# License

This project is developed for educational, research, and portfolio purposes.


⭐ If you find this project interesting, consider giving it a star.