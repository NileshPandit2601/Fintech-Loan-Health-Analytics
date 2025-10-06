# Fintech Loan Health Analytics

<p align="center">
  <img src="https://img.shields.io/badge/Google-BigQuery-blue?logo=googlebigquery&logoColor=white" alt="BigQuery Badge">
  <img src="https://img.shields.io/badge/Looker-Studio-orange?logo=looker&logoColor=white" alt="Looker Studio Badge">
  <img src="https://img.shields.io/badge/Cloud--Native-Solution-success?logo=googlecloud&logoColor=white" alt="Cloud Native">
  <img src="https://img.shields.io/badge/Self--Service-Analytics-informational" alt="Self-Service Analytics Badge">
</p>

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

- ✅ Cloud-native pipeline using Google Cloud tools  
- ✅ Processed & joined raw datasets in BigQuery  
- ✅ Built KPI-driven dashboards in Looker Studio  
- ✅ Automated refresh schedules for real-time insights  
- ✅ Screenshot documentation included for clarity  

---

## 🏗️ Project Parts  

### 🔹 Part 1: Collect, Store & Process Data in BigQuery  
- Explored `fintech` dataset (customers and loans tables)  
- Imported CSV from Cloud Storage into `state_region`  
- Joined tables and created new ones using CTAS  
- Worked with nested records & performed deduplication  
- Aggregated key metrics (e.g. loan count by year)

### 🔹 Part 2: Analyze & Activate Data in Looker  
- Built an interactive dashboard titled "Loan Insights"  
- Created pie charts, bar graphs, KPIs and data tables  
- Highlighted insights like income segmentation & loan status  
- Configured hourly/daily refresh schedules  
- Optimized layout and improved dashboard accessibility  

---

## 📄 Executive Summary

A detailed Executive Summary of this project is available here:  
📎 [Executive Summary PDF](executive_summary.pdf)

---

## ✅ Conclusion

This project illustrates how modern cloud-based tools like BigQuery and Looker Studio can be effectively combined to transform raw financial data into meaningful, self-service business intelligence. From scalable data processing to actionable dashboarding, this pipeline enables data-driven decision-making across the loan lifecycle.

Future improvements could include:  

- Integrating real-time loan transaction data  
- Deploying predictive models for credit risk assessment  
- Implementing role-based access to dashboards  

---

## 🗂️ Project Structure

```bash
Fintech-Loan-Health-Analytics/
│
├── README.md                # Project documentation
├── pipeline.png             # Cloud data flow diagram
├── dashboard.jpg            # Final Looker dashboard screenshot
├── executive_summary.pdf    # PDF of project summary
│
└── images/
    ├── bigquery/            # Part 1 screenshots (data engineering)
    └── looker/              # Part 2 screenshots (dashboarding)
