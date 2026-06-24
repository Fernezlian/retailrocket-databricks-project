# 📊 RetailRocket Data Project (Databricks + SQL + Python)

## 📌 Overview

This project analyzes user behavior from an e-commerce dataset using Databricks, SQL, and Python.  
The main goal is to build a complete data pipeline, perform exploratory analysis, and apply time series forecasting to predict future trends in user activity.

---

## 🗂 Dataset

The dataset used in this project is the **RetailRocket E-commerce Dataset**, available on Kaggle:

https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset

It contains:

- 2.7M+ user interaction events
- Types of events:
  - `view`
  - `addtocart`
  - `transaction`
- Over 1.4M unique users

---

## 🧱 Data Architecture

This project follows the **Medallion Architecture**, a widely used pattern in Data Engineering:

### 🥉 Bronze Layer (Raw Data)
- Raw data ingestion from source
- Stored without transformations

### 🥈 Silver Layer (Cleaned Data)
- Data cleaning and normalization
- Timestamp conversion
- Removal of invalid or null records

### 🥇 Gold Layer (Business Metrics)
- Aggregations for analysis
- KPI tables and business insights
- Example:
  - Conversion funnel
  - User activity metrics

---

## ⚙️ Tech Stack

- Databricks
- Apache Spark
- SQL
- Python (Pandas, Matplotlib)
- Prophet (Time Series Forecasting)

---

## 📊 Data Analysis

### User Behavior

The following analyses were performed:

- Event distribution (views, carts, purchases)
- Top-performing items
- User engagement patterns

### Conversion Funnel

A funnel analysis was built to track user journey: