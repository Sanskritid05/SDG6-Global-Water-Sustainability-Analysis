# 💧 Global Water Sustainability Dashboard (SDG 6)

## 📌 Overview

In alignment with **World Water Day (March 22)**, this project analyzes global water sustainability using data from the United Nations SDG 6 Data Portal. The goal is to provide a comprehensive, data-driven view of water access, sanitation, resource management, wastewater treatment, and ecosystem health across countries.

This project demonstrates end-to-end data analytics — from data cleaning to dashboard development — using Excel and Power BI.

---

## 📊 Data Source

* United Nations SDG 6 Data Portal
* https://sdg6data.org

Datasets used:

* Drinking Water
* Sanitation & Hygiene
* Water Availability & Use
* Integrated Water Resources Management (IWRM)
* Water Quality & Wastewater
* Water-related Ecosystems

---

## 🧹 Data Preparation

Data preprocessing was performed using **Excel and Power Query**:

* Cleaned inconsistent country names
* Removed regional aggregates (e.g., "Western Europe")
* Standardized indicator names using lookup tables
* Handled missing values and formatting issues
* Ensured consistency across datasets before integration

---

## 🚫 Data Handling Decisions

To maintain analytical accuracy:

* Removed non-essential columns (bounds, reporting type, source fields)
* Excluded mixed-granularity data (regions vs countries)
* Avoided combining indicators with different units
* Repositioned limited datasets instead of forcing misleading KPIs

---

## 📈 Dashboard Features

* Multi-page Power BI dashboard with navigation tabs
* KPI cards for each theme
* Top & Bottom 5 country comparisons
* Time-series trend analysis
* Interactive slicers for dynamic filtering
* Clean and consistent UI design

---

## 📊 Key Insights

* Developed regions show near-universal access to safe drinking water, while sanitation gaps persist in several countries
* Strong governance (IWRM scores) does not always align with financial capability
* Wastewater treatment levels vary significantly, indicating uneven infrastructure development
* Ecosystem indicators highlight environmental degradation in specific regions

---

## 🎯 Outcome

This project highlights the importance of integrating multiple indicators to understand water sustainability holistically. It demonstrates how data visualization can uncover disparities, support policy insights, and drive informed decision-making.

---

## ⚠️ Key Learning

> Not all datasets are equally informative — understanding data structure, granularity, and limitations is crucial before analysis.

---

## 🛠 Tools Used

* Microsoft Excel
* Power Query
* Power BI

---

## 🔗 Project Output

(Add your Power BI Public Link here)

---

## 🙌 Acknowledgements

* United Nations SDG 6 Data Portal for open-access datasets
