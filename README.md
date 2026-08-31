# US-Companies-Financial-Analysis

## Overview

An end-to-end financial analysis project evaluating **226 US company records** using industry benchmarking, financial ratios, SQL screening, and Power BI visualization.

The goal was to identify companies with stronger financial fundamentals relative to their industry peers.

**Note:** This is a financial screening and benchmarking project, not a stock-price prediction or investment recommendation.

---

**Business Question
Which companies demonstrate stronger financial health compared with their industry peers?**

The analysis focuses on:
- Profit Margin
- Revenue Growth
- Current Ratio
- ROA
- Debt-to-Equity
- ROE

**Tools**

**Excel →** Data cleaning, industry benchmarking, company scoring

**SQL →** Financial screening, industry analysis, ranking and valuation analysis

**Power BI →** Interactive financial dashboard and company/industry comparison

---

## Methodology

Each company's financial ratios were compared with its **industry average.**

A company received:
- **1 point** when a metric performed better than its industry benchmark
- For Debt-to-Equity, **1 point** when leverage was lower than the industry average

The resulting Financial Health Score ranges from **0--6**.

**Key Findings**
- Average Financial Health Score: **~2.33 / 6**
- **3 companies** achieved the maximum score of 6.
- **26 companies** were classified as Strong.
- **37 companies** were classified as Good.
- **126 companies** were classified as Weak.
- Strong financial performance was distributed across multiple industries rather than concentrated in one sector.
- High ROE did not always indicate stronger financial health because leverage also influenced company performance.
- Profitability, growth, and financial ratios varied significantly across industries, supporting the use of industry-relative benchmarking.

---

## SQL Analysis

SQL was used to:
- Identify companies with the highest Profit Margin, Revenue Growth, and ROE
- Compare financial performance across industries
- Screen companies using multiple financial criteria
- Rank companies within industries using RANK() and PARTITION BY
- Analyze ROE against Debt-to-Equity and valuation metrics
- Identify large-cap companies with stronger fundamentals

---

## Power BI Dashboard
The dashboard contains three pages:

**1. Financial Overview**
KPIs, top companies, industry comparisons, and ROE vs Debt-to-Equity.

**2. Company Deep Dive**
Company-level financial and valuation metrics including EV/Revenue,
EV/EBITDA, Price-to-Book, PEG Ratio, and Forward P/E.

**3. Industry Analysis**
Comparison of Profit Margin, Revenue Growth, ROA, ROE, and
Debt-to-Equity across companies and industries.

**Key Skills Demonstrated**
**Excel:** Data cleaning, PivotTables, XLOOKUP, benchmarking, financial
scoring

**SQL:** Aggregation, filtering, CASE WHEN, CTEs, window functions,
financial screening

**Power BI:** DAX measures, KPI cards, slicers, financial
visualizations, dashboard design

**Limitations**
- The Financial Health Score gives equal weight to all six metrics.
- Missing financial values were retained and excluded from relevant calculations.
- The dataset contains **226 records and 225 unique company names.**
- The analysis evaluates financial fundamentals and does not predict future stock prices.

---

## Outcome
This project demonstrates an end-to-end financial analytics workflow:

**Financial Data → Excel Benchmarking → SQL Analysis → Power BI Dashboard**
It provides a structured approach to comparing company fundamentals, identifying stronger financial performers, and communicating financial insights through an interactive dashboard.
