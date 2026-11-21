# Supply Chain Delivery & Profitability Analytics (DataCo Dataset)

An end-to-end data analytics project analyzing **180,519 supply chain records** from the DataCo Smart Supply Chain dataset using **Python** for data cleaning and feature engineering, and **Tableau** for interactive visual analytics.

---

## Project Objectives
- Identify shipping delay bottlenecks across delivery modes and global markets.
- Analyze monthly revenue and profit trends over time (`2015–2018`).
- Evaluate average profit margins across different shipping modes.

---

## Data Cleaning & Feature Engineering (Python)
- **Data Cleaning:** Dropped empty and sensitive columns (`Product Description`, customer PII fields), verified duplicates, and handled minor missing values.
- **Engineered Metrics:**
  - `Shipping_Delay_Days`: Difference between actual shipping days and scheduled shipment days.
  - `Delivery_Performance`: Categorized orders into **Delayed**, **Early**, and **On Time**.
  - `Profit_Margin_Pct`: Order-level profit margin percentage (`Benefit per order / Sales * 100`).

---

## Dashboard Overview
![Supply Chain Dashboard](screenshots/dashboard_overview.png)

### Key Visuals
1. **Delivery Performance Overview:** Delayed orders account for the largest share (~103K+ orders), followed by Early (~43K) and On Time (~33K).
2. **Monthly Revenue & Profit Trend:** Tracks monthly sales and order profit from `2015-01` to `2018-01`.
3. **Regional & Market Sales Breakdown:** Compares sales across Africa, Europe, LATAM, Pacific Asia, and USCA segmented by delivery performance—with Europe and LATAM leading overall sales volume.
4. **Profit Margin by Shipping Mode:** First Class (`11.34%`) yields the highest average profit margin, followed by Standard Class (`10.80%`), Second Class (`10.61%`), and Same Day (`10.57%`).

---

## Tech Stack
- **Python:** Pandas, NumPy (Data Cleaning & Feature Engineering)
- **Tableau Public:** Visual Analytics & Dashboard Design

---

## Dataset Reference
- **Source:** DataCo Smart Supply Chain for Big Data Analysis (Kaggle)
