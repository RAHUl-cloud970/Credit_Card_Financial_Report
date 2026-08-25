# 💳 Credit Card Financial Dashboard

An interactive Power BI dashboard analyzing credit card customer demographics and transaction behavior, built on data ingested through a PostgreSQL pipeline.

---

## 📊 Project Overview

- **Total Revenue:** 55.3M
- **Total Interest Earned:** 7.84M
- **Total Transaction Amount:** 44.5M
- **Total Transactions:** 656K+
- **Customer Satisfaction Score (CSS):** 3.19

The dashboard is split into two report pages:
1. **Customer Report** — demographic breakdown (age, income, education, marital status, job type, geography)
2. **Transaction Report** — card-tier performance, quarterly trends, expenditure type, and payment channel (chip/swipe/online) analysis

---

## 🛠️ Tech Stack

- **Database:** PostgreSQL
- **ETL:** SQL (`COPY` commands for CSV ingestion, incremental weekly loads)
- **Visualization & Modeling:** Power BI Desktop, DAX

---

## 🗂️ Data & Files

| File | Description |
|---|---|
| `SQL Query - Financial Dashboard Data.sql` | Table creation + CSV import scripts (PostgreSQL) |
| `credit_card.csv` / `customer.csv` | Base transaction and customer data |
| `cc_add.csv` / `cust_add.csv` | Week-53 incremental data load |
| `Credit_Card_Report.pbix` | Power BI report file (open in Power BI Desktop) |
| `CCRT.pdf` / `CCTR1.pdf` | Exported static views of the dashboard |

---

## 🔑 Key Insights

- Blue & Silver card categories drive **93% of total transaction volume**
- Top 3 states (TX, NY, CA) contribute roughly **68% of revenue**
- Card activation rate: **57.5%**; overall delinquency rate: **6.06%**
- Male customers contribute marginally higher revenue (31M) than female customers (26M)
- Graduate-level customers are the single largest revenue-contributing education segment

---

## ⚙️ How to Run

1. Set up a PostgreSQL database and run `SQL Query - Financial Dashboard Data.sql` to create tables and import the CSV files (update file paths in the script to match your local setup).
2. Open `Credit_Card_Report.pbix` in Power BI Desktop.
3. Update the data source connection to point to your PostgreSQL instance.
4. Refresh the report.

---

## 👤 Author

**RAHUl-cloud970**
