# Fintech Loan Health Analytics

> **A cloud-native, self-service analytics project combining Google BigQuery and Looker to collect, process, store, analyze and activate loan data for actionable insights.**

---

## 📌 Overview  
This repository contains my capstone project demonstrating end-to-end data analytics in a fintech loan scenario.  
The project is split into two parts:  

- **Part 1 – Data Engineering in BigQuery**  
  Collecting, storing, and processing raw loan data using Google BigQuery.  
- **Part 2 – Data Visualization in Looker**  
  Analyzing and activating data through dashboards built in Looker Studio (Enterprise).

The workflow reflects a real-world cloud data pipeline and shows my ability to work with self-service analytics tools in a professional setting.

---

## 🚀 Key Highlights  

- **Cloud-Native Approach** – All data stored and processed in **Google BigQuery**.  
- **Self-Service Analytics** – Interactive dashboards built with **Looker**.  
- **Business Focus** – Answers key loan health questions (loan count by year, top customers by income, percentage of outstanding loans, etc.).  
- **Hands-On Implementation** – Queries, transformations, and dashboard screenshots included.  

---

## 🏗️ Project Parts  

### 🔹 Part 1: Collect, Store & Process Data in BigQuery  
- Created and explored `fintech` dataset (customers and loans tables).  
- Imported CSV from Cloud Storage into a new table (`state_region`).  
- Joined multiple tables and created new tables using **CTAS**.  
- Worked with nested data and deduplicated loan purposes.  
- Created aggregated tables like `loan_count_by_year`.  

### 🔹 Part 2: Analyze & Activate Data in Looker  
- Built dashboard **Loan Insights** with multiple visualizations.  
- Added KPI cards, pie charts, bar charts, and tables for business insights.  
- Implemented automatic refresh schedules for different tiles.  
- Optimized dashboard layout, colors, and accessibility.  
- Documented each challenge with screenshots for portfolio use.  

---

## 🗂️ Project Structure  

```bash
Fintech-Loan-Health-Analytics/
│
├── README.md                # This file
├── pipeline.png             # pipeline diagram
├── dashboard.jpg            # Screenshot of final dashboard
├── executive_summary.pdf    # Executive summary of the project
│
└── images/                  # Screenshots for portfolio
    ├── bigquery/            # Screenshots from Part 1
    └── looker/              # Screenshots from Part 2

Got it 👍 — here’s a clean version you can drop into your `README.md`:

---

### 📄 Executive Summary

A detailed Executive Summary of this project is available [**here**](link-to-your-executive-summary.pdf).

---

### ✅ Conclusion

This project demonstrates how **BigQuery** and **Looker Studio** can be combined to transform raw fintech loan data into actionable insights. By leveraging scalable cloud tools, it streamlines data preparation and visualization, enabling faster, data-driven decisions. Future improvements can include real-time data integration and predictive modeling to further enhance risk assessment and operational efficiency.

---
