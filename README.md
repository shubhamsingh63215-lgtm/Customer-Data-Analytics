# 📊 Customer Churn Data Analytics Portfolio Project

## 📌 Project Overview
An end-to-end data analytics pipeline designed to extract operational metrics from a relational database, process customer transaction data, and identify key drivers behind subscriber churn. This project bridges the gap between structured backend databases and executive-ready data visualizations.

## 🛠️ Tech Stack & Architecture
* **Language:** Python 3.x
* **Database Management:** SQLite (`sqlite3`)
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

## ⚙️ Data Pipeline Stages
1. **Extraction:** Handled explicit schema queries via `sqlite3` to pull unstructured database metrics into structured analytical frames.
2. **Data Cleaning:** Re-mapped categorical text features, formatted raw Unix timestamps to standardized datetime objects, and resolved data type inconsistencies.
3. **Feature Engineering:** Programmatically mapped customer date-of-birth objects against baseline metrics to calculate real-time age groups.
4. **Relational Joining:** Merged isolated demographic, subscription, and platform support tables seamlessly using matching dimensional primary keys.
5. **Exploratory Data Analysis (EDA):** Rendered interactive visual metrics mapping demographic features, monthly billing allocations, and baseline subscription tiers against churn behaviors.

## 📊 Key Insights & Business Performance
* **Baseline Platform Attrition:** The system identified a definitive target **churn rate of 28.57%** across the tracked customer ecosystem.
* **Tier Volatility:** Customers subscribed to the **Basic** plan type exhibited significantly higher churn volatility compared to high-tier premium accounts.
* **Financial Thresholds:** Active accounts tend to maintain higher median monthly spend metrics, whereas churned accounts reflect lower, fragmented billing values.

## 🔮 Future Enhancements & Scalability
* **Interactive BI Dashboarding:** The next phase of this project involves establishing an ODBC connection to port the cleaned SQLite relational schema into Microsoft Power BI.
* **Executive Metrics:** Construct a dynamic tracking dashboard featuring interactive KPI cards for active vs. churned distribution, allowing stakeholders to slice data by geographic country and contract duration.
