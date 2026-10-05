# 📊 Finance Analysis Dashboard — Power BI

An interactive **Finance Analysis Dashboard** built with **Microsoft Power BI** to transform transaction and customer data into clear, actionable financial insights.

The dashboard provides a consolidated view of **transaction performance, revenue, transaction volume, fees, taxes, customer segments, transaction status, gender distribution, states, and transaction types**, with interactive filters for deeper analysis.

![Finance Analysis Dashboard](assets/dashboard-preview.png)

---

## 🎯 Project Objective

The objective of this project is to analyze financial transaction data and build an interactive dashboard that helps users:

- Monitor overall financial performance
- Track transaction volume and transaction value
- Compare performance with the previous year
- Analyze transaction fees and taxes
- Identify high-performing customer segments
- Understand transaction success, failure, and pending rates
- Analyze transaction activity across states and genders
- Compare different transaction types
- Explore data dynamically using interactive filters

---

## 📌 Dashboard Highlights

### KPI Overview

The dashboard provides key financial metrics at a glance:

| KPI | Dashboard Value |
|---|---:|
| **Total Amount** | ₹137.53M |
| **Total Transactions** | 149.4K |
| **Average Transaction Value** | ₹9.20K |
| **Total Fees** | ₹216.94K |
| **Total Tax** | ₹39.04K |

The KPI cards also display year-over-year percentage changes to make performance trends easier to monitor.

---

## 📈 Visual Analysis

### 1. Total Amount by Month

A monthly trend visualization showing how transaction value changes throughout the year and helping identify high and low-performing periods.

### 2. Transaction Status Analysis

A donut chart showing the distribution of:

- Successful transactions
- Failed transactions
- Pending transactions

### 3. Customer Segment Analysis

Compares transaction value across customer segments such as:

- Retail
- Premium
- SME
- Corporate
- Wealth

### 4. State-wise Analysis

Highlights transaction amounts across Indian states to identify regions contributing the most to overall transaction value.

### 5. Transaction Type Analysis

A detailed table comparing transaction types using:

- Amount
- Fees
- Tax
- Number of transactions

### 6. Gender Analysis

Visualizes transaction value distribution between male and female customers.

---

## 🎛️ Interactive Filters

The dashboard includes interactive slicers that allow users to explore the data based on:

- **Year**
- **Dynamic Metric**
- **Occupation**
- **Category**

These filters make the dashboard suitable for both high-level reporting and detailed analysis.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Calculated measures, KPIs, and analytical logic
- **Microsoft Excel / CSV** — Data source and data preparation

---

## 📂 Project Structure

```text
Finance-Analysis-PowerBI/
│
├── README.md
├── Finance_Analysis.pbix
│
├── data/
│   ├── finance_transactions.csv
│   └── customers.csv
│
└── assets/
    └── dashboard-preview.png
```

> The `assets/images/` folder can also be used for dashboard icons and other visual resources used in the Power BI report.

---

## 📊 Data Sources

The project uses two primary datasets:

### `finance_transactions.csv`

Contains transaction-level financial information used for analyzing transaction amounts, fees, taxes, transaction status, transaction type, and related metrics.

### `customers.csv`

Contains customer-related information used to support segmentation and demographic analysis.

The datasets are transformed and modeled in Power BI before being used in the dashboard.

---

## 🔄 Data Analysis Workflow

```text
Raw CSV Data
     ↓
Data Cleaning & Transformation
     ↓
Data Modeling in Power BI
     ↓
DAX Measures & Calculations
     ↓
Interactive Visualizations
     ↓
Finance Analysis Dashboard
```

---

## 💡 Key Insights

Based on the dashboard view:

- The **Retail** customer segment contributes the highest transaction value among the displayed segments.
- **Successful transactions** represent the majority of total transaction value.
- **Maharashtra** is the highest-contributing state among the displayed states.
- **Loan EMI** and **Transfer** are among the major transaction types by amount.
- Monthly transaction value fluctuates throughout the year, highlighting periods of stronger and weaker activity.
- The dashboard provides a quick comparison of transaction value across customer demographics and business categories.

---

## 🚀 How to Use the Dashboard

1. Download or clone this repository.
2. Open `Finance_Analysis.pbix` using **Microsoft Power BI Desktop**.
3. If Power BI asks for the data source location, update the CSV file paths to the files inside the `data/` folder.
4. Refresh the dataset if required.
5. Use the slicers and visual interactions to explore the financial data.

### Requirements

- Microsoft Power BI Desktop
- Access to the included CSV datasets

---

## 📷 Dashboard Preview

The report is designed as an interactive finance analytics dashboard with a clean executive-style layout, KPI cards, trend analysis, segmentation, geographic analysis, and transaction-level comparisons.

---

## 🔮 Possible Future Improvements

- Add a dedicated **Customer Analysis** page
- Add a **Year-over-Year trend analysis** page
- Include profit and profitability metrics
- Add drill-through pages for individual customers and transactions
- Add more advanced forecasting and anomaly detection
- Publish the report to **Power BI Service** for online sharing
- Add automated data refresh capabilities

---

## 👤 Author

**Ayush Gaikwad**

BSc IT | Data Analytics & Business Intelligence Enthusiast

This project was created as part of my **Data Analytics / Power BI portfolio** to demonstrate practical skills in data visualization, business intelligence, data modeling, and analytical reporting.

---

## ⭐ If You Like This Project

If you find this project useful or interesting, consider giving the repository a **⭐ Star** on GitHub.

---

### 📌 Disclaimer

This project is created for **educational and portfolio purposes**. The financial data used in the dashboard is intended for analysis and demonstration and should not be interpreted as real financial advice.
