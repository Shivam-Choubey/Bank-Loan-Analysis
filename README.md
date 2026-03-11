# 🏦 Bank Loan Analysis Dashboard

> A comprehensive Power BI dashboard analyzing bank loan portfolios across key performance indicators — tracking loan applications, funded amounts, repayment patterns, and loan health to support data-driven lending decisions.

---

## 🗂️ Table of Contents

- [Project Overview](#project-overview)
- [Dashboard Previews](#dashboard-previews)
- [Key KPIs & Summary Metrics](#key-kpis--summary-metrics)
- [Loan Performance Analysis](#loan-performance-analysis)
- [Good vs Bad Loan Breakdown](#good-vs-bad-loan-breakdown)
- [Loan Purpose Analysis](#loan-purpose-analysis)
- [Dashboard Features](#dashboard-features)
- [Key Business Insights](#key-business-insights)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)

---

## 📌 Project Overview

This project delivers a multi-page **Bank Loan Analysis Dashboard** in Power BI that gives stakeholders a complete view of the loan portfolio — from high-level KPIs down to individual loan records. The dashboard is designed to help the lending and risk teams monitor portfolio health, identify risk areas, and make informed decisions on loan approvals and interest rate strategies.

---

## 🖥️ Dashboard Previews


### Summary Dashboard
![Summary Page](./summary%20dashboard.jpg)
### Overview Dashboard
![Overview Page](./overview%20dashboard.jpg)
### Details Dashboard
![Details Page](./details%20dashboard.jpg)


---

## 📐 Key KPIs & Summary Metrics

| Metric | Value |
|--------|-------|
| **Total Loan Applications** | 38.6K |
| **Total Funded Amount** | $435.8M |
| **Total Amount Received** | $473.1M |
| **Average Interest Rate** | 12.05% |
| **Average Debt-to-Income Ratio (DTI)** | 13.33% |

---

## 📊 Loan Performance Analysis

### Loan Status Breakdown

| Loan Status | Applications | Funded Amount | Amount Received | Avg DTI | Avg Interest Rate |
|-------------|-------------|---------------|-----------------|---------|-------------------|
| Fully Paid | 32,145 | $351.36M | $411.59M | 13.17% | 11.64% |
| Current | 1,098 | $18.87M | $24.20M | 14.72% | 15.10% |
| Charged Off | 5,333 | $65.53M | $37.28M | 14.00% | 13.88% |
| **Total** | **38,576** | **$435.76M** | **$473.07M** | **13.33%** | **12.05%** |

---

## ✅ Good vs Bad Loan Breakdown

### Good Loans — 86.18%
- **Applications:** 33.2K
- Includes loans with **Fully Paid** and **Current** status
- Represents the healthy, performing portion of the portfolio

### Bad Loans — 13.82%
- **Applications:** 5.3K
- Includes loans with **Charged Off** status
- Smaller in volume but carries significant financial risk

---

## 💼 Loan Purpose Analysis

### Funded Amount by Purpose (Good vs Bad Loans)

| Loan Purpose | Good Loans | Bad Loans |
|--------------|-----------|----------|
| Debt Consolidation | $196M | $36M |
| Credit Card | $52M | $7M |
| Home Improvement | $29M | $4M |
| Other | $26M | $5M |
| Small Business | $15M | $7M |
| Major Purchase | $7M | $2M |

> **Note:** Small Business loans show a disproportionately high bad loan ratio relative to their funded amount, indicating elevated risk in this category.

---

## 📊 Dashboard Features

The dashboard is organized across **3 pages** with the following components:

**Summary Page**
- KPI cards for all top-level metrics
- Good vs Bad loan donut chart
- Loan status breakdown table

**Overview Page**
- Funded amount by purpose — stacked bar chart (Good vs Bad)
- Trend analysis across loan grades and terms
- Geographic state-wise distribution

**Details Page**
- Row-level loan data table with filters
- Individual loan records showing Purpose, Home Ownership, Grade, Funded Amount, Interest Rate, Term, and Verification Status

**Interactive Filters (Slicers)**
- Purpose of Loan
- Grade of Loan (A through G)
- State — geographic filter for state-wise analysis

---

## 💡 Key Business Insights

1. **Strong Portfolio Health** — 86.18% of all loans are classified as Good Loans (Fully Paid or Current), reflecting a well-managed lending portfolio.

2. **Risk Signal in Small Business** — Small business loans have a notably higher proportion of charged-off (bad) loans relative to their total funded amount compared to other categories, signaling a higher-risk segment worth closer monitoring.

3. **Interest Rate & Default Correlation** — Charged-off loans carry a higher average interest rate (13.88%) vs. fully paid loans (11.64%), suggesting that higher-rate borrowers carry greater default risk.

4. **Debt Consolidation Dominates** — The largest loan category with $232M in total funded amount, representing both the highest good loan volume and the highest bad loan exposure — making it the most critical segment to manage.

---

## 🛠️ Tech Stack

- **Visualization:** Microsoft Power BI Desktop
- **Data Source:** Bank loan database / Excel files
- **Features Used:** DAX measures, cross-filtering slicers, multi-page report layout, conditional formatting

---

## 📁 Project Structure

```
bank-loan-analysis/
│
├── Bank Loan Report.pbix       
├── README.md                   
├── overview dashboard.jpg
├── summary dashboard.jpg
├── details dashboard.jpg
└── Bank Loan Analysis.pdf    
```

---

## 🚀 How to Use

1. Open `Bank Loan Report.pbix` in **Microsoft Power BI Desktop**
2. Navigate between the three report pages — **Summary**, **Overview**, and **Details**
3. Use the slicers on the right panel to filter data by:
   - Loan Purpose
   - Loan Grade (A–G)
   - State

---
