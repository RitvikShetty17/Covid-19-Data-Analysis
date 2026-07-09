# 🦠 COVID-19 Global Data Analysis

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-Data%20Analysis-blue?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Dashboard-KPI%20Metrics-orange?style=for-the-badge)

An Exploratory Data Analysis (EDA) project analyzing worldwide COVID-19 statistics across 187 countries — covering total cases, recoveries, deaths, and weekly trends — with an interactive Excel dashboard for decision-making support.

---

## 📌 Project Overview

This project analyzes a global COVID-19 dataset to understand the spread and impact of the pandemic. Using Excel, the project covers data cleaning, KPI calculation, EDA, and an interactive dashboard with slicers for dynamic filtering by country and WHO region.

**Business Questions Answered:**
- Which countries had the highest total cases, deaths, and recoveries?
- What are the recovery and death rates per 100 cases by country?
- Which regions showed the highest weekly percentage increase in cases?
- How do active cases compare across WHO regions?
- Which countries are moving toward stabilization based on weekly trends?

---

## 🗂️ Repository Structure

```
Covid-19-Data-Analysis/
│
└── Covid19.xlsx
    ├── Covid19_data    # Raw dataset (187 countries, 19 features)
    ├── EDA             # Exploratory analysis with charts and summaries
    └── Dashboard       # Interactive dashboard with slicers and KPIs
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Excel** | Data cleaning, EDA, KPI calculation, and dashboard creation |
| **Pivot Tables & Slicers** | Interactive filtering by country and WHO region |
| **Excel Formulas** | KPI metrics — recovery rate, death rate, weekly % change |
| **Bar Charts** | Visual comparison across countries and regions |

---

## 📊 Dataset Features

The raw dataset (`Covid19_data` sheet) contains **187 countries** with **19 columns**:

| Column | Description |
|---|---|
| Total Cases / Confirmed | Cumulative confirmed cases |
| Active | Currently active cases |
| Recovered / Deaths | Total recoveries and fatalities |
| New Cases / New Deaths | Daily new figures |
| Recovered / 100 Cases | Recovery rate KPI |
| Deaths / 100 Cases | Death rate KPI |
| 1 Week Change / % Increase | Weekly trend metrics |
| WHO Region | Regional classification |

---

## 📈 Dashboard Highlights

The interactive Excel dashboard includes:

- **KPI Cards** — Recovery rate, death rate, deaths per 100 recovered
- **Top Affected Countries** — Ranked by total cases and deaths
- **WHO Region Breakdown** — Active cases and recoveries by region
- **Weekly Trend Analysis** — Countries with highest 1-week % increase
- **Slicers** — Dynamic filtering by Country/Region and WHO Region

---

## 💡 Key Insights

- Countries with the highest weekly percentage increase served as early outbreak signals
- Recovery rates vary significantly across WHO regions, reflecting healthcare capacity differences
- Weekly trend analysis identified countries moving toward stabilization vs. escalation
- Death rate per 100 cases highlighted regions with strained medical infrastructure

---

## 🚀 How to Use

1. Open `Covid19.xlsx` in Microsoft Excel
2. Navigate to the **Dashboard** sheet for the interactive view
3. Use the **slicers** to filter by country or WHO region
4. Visit the **EDA** sheet for detailed charts and statistical summaries

---

## 👤 Author

**Ritvik Shetty**
[LinkedIn](https://www.linkedin.com/in/ritvikshetty23/) · [GitHub](https://github.com/RitvikShetty17)
