# Fintech Loan Health Analytics

> **A cloud-native, self-service analytics project combining Google BigQuery and Looker Studio to collect, process, store, analyze, and activate loan data for actionable insights.**

---

### Project Purpose

To demonstrate an **end-to-end cloud data analytics solution** that leverages Google BigQuery and Looker Studio for managing and analyzing large-scale fintech loan data. The project showcases how modern, serverless tools can create efficient, scalable, and self-service analytics environments.

---

### Business Case

In the fintech industry, understanding loan health and customer behavior is critical for minimizing defaults and optimizing lending strategies.
However, traditional data pipelines are often siloed, slow, and manually intensive.
This project provides a **cloud-native architecture** that enables real-time data access, automated reporting, and business intelligence for loan portfolio monitoring.

---

### Project Goal

To design and implement a **Google Cloud-based loan analytics pipeline** that:

* Ingests and processes raw loan data in **BigQuery**
* Builds analytical datasets for KPI tracking and trend analysis
* Develops **interactive dashboards** in Looker Studio
* Enables **self-service analytics** for data-driven decision-making across teams

---

## Project Overview

This project simulates a fintech organization’s loan portfolio monitoring process.
It is divided into two parts:

* **Part 1 – Data Engineering in BigQuery**: Collect, store, and process raw customer and loan data.
* **Part 2 – Data Visualization in Looker Studio**: Build dashboards that track loan performance and borrower trends.

The pipeline represents a real-world enterprise setup — demonstrating your ability to manage data transformation, modeling, and visualization in a **cloud-native environment**.

---

## Key Highlights

* End-to-end **Google Cloud-based pipeline** using BigQuery and Looker Studio
* Data cleaning, transformation, and aggregation using SQL in BigQuery
* KPI-driven **interactive dashboards** for loan performance insights
* Automated refresh schedules for near real-time data updates
* Executive Summary and screenshots for complete project transparency

---

## Project Parts

### Part 1: Data Collection, Storage, and Processing (BigQuery)

* Imported customer and loan datasets into BigQuery from Cloud Storage
* Created normalized tables and relationships using CTAS queries
* Performed data deduplication and handled nested records
* Generated aggregated metrics such as **loan volume by year** and **region**
* Created analytical datasets for dashboard consumption

### Part 2: Data Analysis and Visualization (Looker Studio)

* Built an interactive dashboard titled **“Loan Insights”**
* Designed charts, KPIs, and data tables to show borrower demographics, loan status, and repayment trends
* Highlighted insights like **income segmentation**, **loan approval ratios**, and **default rates**
* Configured scheduled data refreshes for automated reporting
* Optimized visual layout for clarity and accessibility

---

## Business Impact

This project demonstrates how **cloud analytics** can replace static reporting with dynamic, real-time intelligence.
By centralizing loan data and enabling self-service analytics, organizations can:

* **Monitor loan performance** across geographies and income segments
* **Reduce manual reporting time** through automation and scheduled refreshes
* **Identify default risks early** with interactive dashboards
* Enable **data democratization**, allowing non-technical users to access insights easily

The resulting system enhances **decision accuracy**, **operational efficiency**, and **loan portfolio visibility** across the business.

---

## Next Steps

* Integrate **real-time loan transactions** via Google Pub/Sub or Cloud Functions
* Extend analytics with **predictive modeling** for credit risk scoring
* Implement **role-based access controls** in Looker Studio
* Expand data sources to include repayment history and customer credit ratings
* Deploy **end-to-end orchestration** using Cloud Composer or Dataform

---

## Conclusion

This project showcases how modern cloud technologies — particularly **BigQuery** and **Looker Studio** — can work together to transform raw financial data into actionable insights.
By applying principles of scalability, automation, and accessibility, the solution delivers a robust framework for **data-driven financial analytics**.

---

## Project Structure

```bash
Fintech-Loan-Health-Analytics/
│
├── README.md                # Project documentation
├── pipeline.png             # Cloud data flow diagram
├── dashboard.jpg            # Final Looker dashboard screenshot
├── executive_summary.pdf    # Project summary
│
└── images/
    ├── bigquery/            # Part 1 screenshots (data engineering)
    └── looker/              # Part 2 screenshots (dashboarding)
```

---
