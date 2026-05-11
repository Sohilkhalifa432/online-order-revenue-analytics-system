# 📦 Online Order Revenue Analytics System

> Turning 400,000+ raw order transactions into decisions that can actually grow a business.

---

## 📌 Project Overview

The **Online Order Revenue Analytics System** is an end-to-end data analytics project built on a real-world dataset of **400,000+ online order transactions**. It covers the full analytics pipeline — from raw data ingestion using SQL, to data cleaning and EDA in Python, to an interactive Power BI dashboard — all aimed at answering one core business question:

> **How can an online retail business grow revenue — and where exactly is it losing money?**

Most businesses track total sales but miss the patterns hidden inside their data. This project digs deep into 4 lakh+ order records to surface those patterns.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **SQL** | Built a custom database from scratch, loaded raw order data, and used queries to extract and structure data for analysis |
| **Python (Pandas, Matplotlib, Seaborn)** | Cleaned 400K+ records, handled null values, removed inconsistencies, converted raw fields into meaningful business information, and performed full Exploratory Data Analysis (EDA) |
| **Power BI** | Built an interactive dashboard to visualize revenue trends, product performance, customer segments, return analysis, and country-wise distribution |

---

## 📂 Project Structure

```
online-order-revenue-analytics/
│
├── data/
│   └── orders_raw.csv               # Raw dataset (400K+ transactions)
│
├── sql/
│   └── database_setup.sql           # DB creation, data loading & queries
│
├── python/
│   ├── data_cleaning.ipynb          # Null handling, type conversion, deduplication
│   └── eda_analysis.ipynb           # Full EDA — revenue, products, customers, geography
│
├── dashboard/
│   └── revenue_analytics.pbix       # Power BI interactive dashboard
│
└── README.md
```

---

## ❓ Key Business Questions & Findings

### 📅 Q1: When does the business make most of its revenue?

**A:** 60% of peak revenue is concentrated in just **3 months (Sep–Nov)**. The festive season drives a **51% single-month revenue spike** — from £6.15L in August to £9.29L in September. The lowest-performing month is **April (£4.25L)**, attributed to a post-financial year reset and absence of major festivals.

---

### 🔴 Q2: Where is the business silently losing money?

**A:** **"Paper Craft Little Birdie"** caused **£1,68,469 in revenue loss through returns** — more than any top-selling product earned in net revenue. This product wasn't even on the top sellers list, making it an **invisible drain** on the business that would go undetected without deep analysis.

---

### 👥 Q3: Who is actually keeping the business alive?

**A:** Just **867 customers (top 20%)** generate **75% of total revenue**, while **3,472 customers (bottom 80%)** contribute only **25%**. The **Pareto Principle**, live and confirmed in real transactional data.

---

### 🌍 Q4: Is the business geographically diverse?

**A:** The **UK generates £67,47,156** — nearly **24× more** than the 2nd-ranked market, Netherlands (£2,84,661). International presence remains very low, with significant **untapped global potential**.

---

## 💡 3 Actionable Business Decisions

| # | Decision | Insight Behind It |
|---|----------|-------------------|
| 1 | **Prepare before the festive season** | Scale inventory and marketing in August, before the Sep–Nov revenue surge hits |
| 2 | **Protect the top 20% of customers** | 867 people hold up 75% of total revenue — a targeted loyalty program directly protects business stability |
| 3 | **Fix the return problem immediately** | Paper Craft Little Birdie needs an urgent quality review — reducing returns is direct, recoverable revenue |

---

## 📊 Dashboard Highlights (Power BI)

![Power BI Dashboard](https://github.com/Sohilkhalifa432/online-order-revenue-analytics-system/blob/main/dashboard.jpeg?raw=true)

The interactive dashboard covers:
- 📈 Monthly & yearly **revenue trends**
- 🏆 **Top products** by revenue and return rate
- 👤 **Customer segmentation** (Pareto analysis)
- 🔄 **Return analysis** by product and region
- 🌐 **Country-wise revenue distribution**

---

## 🚀 How to Run This Project

### 1. Set Up the Database
```sql
-- Run the SQL setup script
source sql/database_setup.sql
```

### 2. Run the Python Notebooks
```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook python/data_cleaning.ipynb
jupyter notebook python/eda_analysis.ipynb
```

### 3. Open the Power BI Dashboard
- Open `dashboard/revenue_analytics.pbix` in **Power BI Desktop**
- Refresh the data source if needed

---

## 📈 Dataset

- **Size:** 400,000+ records
- **Type:** Real-world online order transactions
- **Fields include:** Order ID, Product, Quantity, Unit Price, Customer ID, Country, Order Date, Return Status

---

## 🙋‍♂️ About This Project

This project isn't just about charts — it's about turning raw order data into **decisions that can actually grow a business**. Every insight here maps directly to a business action.

Built as a portfolio project to demonstrate end-to-end data analytics skills across SQL, Python, and Power BI.

---

## 📬 Connect

If you found this project interesting or have feedback, feel free to connect on [LinkedIn](#) or raise an issue in this repo!

---

*⭐ Star this repo if you found it helpful!*
