<div align="center">

# 🏥 HealthConnect Clinic — Data Analytics Track

### AnalystLab Africa Experience Lab | Improving Patient Appointment Attendance Using Data and AI

![Python](https://img.shields.io/badge/Python-1C7293?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1C7293?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-21295C?style=for-the-badge&logo=jupyter&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-21295C?style=for-the-badge&logo=powerbi&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-E8734A?style=for-the-badge)

</div>

---

## 📋 Project Overview

HealthConnect Clinic is a fictional healthcare provider facing a significant operational challenge: patients frequently miss scheduled appointments, disrupting clinic efficiency and patient care. This project explores how data analysis can help the clinic understand and reduce missed appointments (no-shows).

> **Central Project Question**
> How can HealthConnect Clinic use data and AI to reduce missed appointments and improve the patient support experience?

This repository documents the **Data Analytics track** contribution to the shared, multi-track HealthConnect Experience Lab under the AnalystLab Africa programme.

---

## 🎯 My Role — Data Analytics Track

My responsibility is to explore the appointment dataset, assess data quality, define business questions, calculate meaningful KPIs, and build an interactive dashboard that communicates findings clearly to decision-makers.

---

## 📊 Dataset

| Detail | Description |
|---|---|
| **File** | `HealthConnect_Appointment_Data.csv` |
| **Records** | 5,000 fictional, anonymised appointment records |
| **Fields** | 18 columns — demographics, appointment details, booking history, reminders, outcomes |
| **Reference** | `HealthConnect_Data_Dictionary.xlsx` — full variable definitions and expected value ranges |

---


---

## ✅ Week 4 — Problem Understanding & Initial Analysis

**Status: Complete**

- Reviewed the dataset structure and Data Dictionary
- Conducted a full data quality assessment (missing values, duplicates, data types, logical consistency)
- Confirmed overall **no-show rate of 48.5%**, validating the scale of the business problem
- Defined 6 business questions and proposed 5 KPIs, each linked to a question

📄 [`docs/initial_analysis_document.docx`](docs/initial_analysis_document.docx) · [`docs/week4_project_summary.docx`](docs/week4_project_summary.docx)

---

## ✅ Week 5 — Exploratory Analysis, KPI Development & Dashboard

**Status: Complete**

- Cleaned date fields and created derived columns (`is_no_show`, `distance_band`, `lead_time_band`, `had_previous_noshow`)
- Ran exploratory analysis across 9 variables to identify no-show drivers
- Calculated all 5 KPIs with full interpretation
- Built an initial interactive Power BI dashboard
- Documented 5 business insights and 5 evidence-based recommendations
- Shared feature-relevance findings with the Data Science track

📄 [`docs/initial_healthconnect_analytics_report.docx`](docs/initial_healthconnect_analytics_report.docx) · [`docs/week5_project_summary.docx`](docs/week5_project_summary.docx)
📊 [`dashboard/healthconnect_dashboard.pdf`](dashboard/healthconnect_dashboard.pdf)

---

## 📈 KPIs & Key Findings

| KPI | Value | Business Question |
|---|---|---|
| Overall No-Show Rate | **48.5%** | What is the scale of the attendance problem? |
| No-Show Rate by Booking Lead Time | **24.8% → 54.4%** | Does lead time relate to attendance? |
| No-Show Rate by Distance Band | **46.5% → 68.1%** | Does distance affect attendance? |
| Repeat No-Show Rate | **55.4% vs 43.5%** | Does prior history predict future behaviour? |
| No-Show Rate by Reminder Channel | **45.8% → 51.4%** | Do reminders reduce no-shows? |

**Strongest drivers:** Booking lead time and distance to clinic — both show a much larger effect than reminder channel, appointment type, day, waiting time, gender, or age group.

---

## 🛠️ Tools Used

- **Python** (pandas) — data cleaning, feature engineering, exploratory analysis
- **Jupyter Notebook** (via VS Code) — analysis environment
- **Power BI Service** — interactive dashboard with DAX measures and slicers

---

## 🗺️ Roadmap

- [x] **Week 4** — Problem understanding, data quality assessment, KPI proposal
- [x] **Week 5** — Data cleaning, EDA, KPI calculation, initial dashboard, insights & recommendations
- [ ] **Week 6+** — Dashboard refinement, further segmentation, continued cross-track collaboration

---

## 🤝 Cross-Track Collaboration

Shared with the **Data Science track**: booking lead time, distance to clinic, and previous no-show history are the strongest predictors of no-shows found in this analysis — intended to inform their feature selection for a no-show prediction model.

---

## 👤 Author

**Manjusri**
MSc Artificial Intelligence (Industrial Placement), University of East London

[![LinkedIn](https://img.shields.io/badge/LinkedIn-21295C?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-1C7293?style=for-the-badge&logo=github&logoColor=white)](#)

---

<div align="center">

*Part of the AnalystLab Africa Data Analytics Internship / Experience Lab programme.*

</div>
