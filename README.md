# Simulated Healthcare Project

This project showcases a **simulated end-to-end data pipeline** for reporting and analyzing **HEDIS quality metrics**, **Risk Adjustment and Audit Management(RAAM)** data, and **clinical event tracking** (ADT) using data sourced from Epic's Analytics based data models - like (Clarity/Caboodle).

> ⚠️ **Please Note:** All data in this project is synthetically generated and does **not** contain any PHI. This project is for demonstration purposes only and aligns with HIPAA guidelines.

---

## 🔍 Project Overview

### Goals:
- Simulate healthcare reporting workflows using mock Epic data
- Model a SQL-based data pipeline from ingestion to dashboard
- Showcase clinical and claims data transformation for quality and audit insights

---

## 🏗️ Pipeline Architecture

1. **Data Ingestion**: Simulated CSV files act as extracts from Epic Chronicles
2. **Transformation**: SQL scripts and Python notebooks clean, join, and aggregate data
3. **Reporting**: Interactive dashboards visualize HEDIS & RAAM metrics
4. **Governance**: Documentation outlines metric definitions and audit standards

---

## ⚙️ Tools Used

- **SQL** (pulled data using Clarity/Caboodle data models)
- **Python** (Pandas, NumPy, Matplotlib; data exploration and modeling)
- **Power BI** (dashboard visuals)
- **Draw.io** (for pipeline diagram)

---

## 📈 Key Features

- 📊 **HEDIS Reporting**: Breast Cancer Screening, HbA1c Control, Blood Pressure Management
- 🩺 **RAAM Insights**: Suspect conditions, audit gaps, and chart retrieval flags
- 📅 **ADT Event Monitoring**: Simulates admission, discharge, and transfer trends
- 🧠 **Predictive Modeling**: Identifies members with high risk based on past encounters

---

## 🗃️ Example Files

- `sql/extract_hedis_measures.sql`: Sample SQL for quality measure pulls
- `notebooks/data_transformation.ipynb`: Cleans and joins datasets
- `dashboards/powerbi_dashboard_screenshot.png`: Preview of the interactive report
- `docs/metric_definitions.md`: Explanation of simulated HEDIS/RAAM metrics

---

## 📌 About Me

I’m a healthcare data analyst working with Epic’s Clarity & Caboodle data models, supporting payer-provider interoperability, risk adjustment and audit management, and quality analytics. This repo reflects the structure and strategy I use in my real-world work — adapted for the open-source world.
