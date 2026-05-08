
# Port Authority of NY & NJ — Tunnels & Bridges Traffic Analytics

![Status](https://img.shields.io/badge/Status-Complete-green)
![Course](https://img.shields.io/badge/Course-BANL%206900--02-blue)
![University](https://img.shields.io/badge/University-New%20Haven-navy)
![Records](https://img.shields.io/badge/Records-643%2C802-orange)

## About This Project

The Port Authority of New York and New Jersey operates six major 
bridges and tunnels connecting New York City and New Jersey, 
handling over 1.45 billion vehicle crossings between 2013 and 2025. 
As part of our Business Analytics Capstone at the University of New Haven, 
our team was tasked by the Port Authority to analyze 13 years of hourly 
traffic data and answer six critical business questions.

We built a complete end-to-end data analytics pipeline starting from 
raw data files of 5.3 million hourly records, cleaning and integrating 
four source datasets into a final master dataset of 643,802 records 
with 47 variables, performing exploratory data analysis, building 
machine learning models using H2O AutoML and Python scikit-learn, 
forecasting facility usage through 2030, and presenting all findings 
through an interactive Power BI dashboard.

The project covers the full spectrum of business analytics work 
including data engineering, statistical analysis, machine learning, 
time series forecasting, data visualization, and management reporting. 
Every finding is backed by exact numbers from the data and translated 
into actionable recommendations for Port Authority leadership.

---

## Business Questions Answered

| Question | Answer |
|----------|--------|
| Q1: Top 5 Factors | Time of Day, Day of Week, Season, Facility, Vehicle Type |
| Q2: Toll Violations | 81.1M violations — GWB accounts for 51.9% |
| Q3: Busiest Times | Peak hour 5PM, Peak day Saturday, Peak month August |
| Q4: Congestion Pricing | Uniform 60% decline — no traffic shifting confirmed |
| Q5: AutoML Forecast | GBM model RMSE 29.73, R squared 0.9998 — 2030 horizon |
| Q6: Python Replication | GradientBoostingRegressor confirms identical results |

---

## Key Findings

- **1.45 billion** total vehicles analyzed across 6 facilities
- **81.1 million** toll violations identified and broken down
- **GWB dominates** at 42.6% of all traffic and 51.9% of violations
- **Congestion pricing** caused uniform 60% decline — no rerouting
- **GBM model** achieves R squared of 0.9998 on 643,802 hourly records
- **Forecast** projects stable 122M annual vehicles through 2030

---

## Dataset

| Attribute | Value |
|-----------|-------|
| Records | 643,802 hourly |
| Facilities | 6 Port Authority crossings |
| Period | 2013 to 2025 |
| Variables | 47 columns |
| Source | Port Authority of NY and NJ |

---

## Tools and Technologies

| Category | Tools |
|----------|-------|
| Programming | Python 3, Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Microsoft Power BI |
| Development | Google Colab, Jupyter Notebook, Anaconda |
| AutoML | H2O AutoML, H2O Flow Interface |
| ML Library | scikit-learn GradientBoostingRegressor |
| Version Control | GitHub |
| Documentation | Microsoft Word, Microsoft Excel |

---

## Repository Structure
