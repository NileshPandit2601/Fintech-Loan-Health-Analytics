# Fintech Loan Health Analytics – Cloud Data Analytics Capstone

**Capstone project demonstrating cloud-based analytics, ETL pipelines, star schema data modeling, and actionable loan portfolio insights for fintech operations.**

---

## Project Overview
This project simulates a real-world scenario at **TheLook Fintech**, a fintech startup providing loans to independent online store owners.  
As a cloud data analyst, my goal was to help the Treasury Department leverage **cloud-native analytics tools** to monitor loan performance, manage risk, and make timely, data-driven decisions.

The project showcases **end-to-end cloud data analytics skills**, including:  
- Data collection, transformation, and storage in **Google BigQuery**  
- **Star schema-based data modeling** for optimized queries  
- Building **self-service dashboards** with **Looker Enterprise**  
- Delivering **actionable insights** for business stakeholders  

---

## Business Understanding
The Treasury Department required insights to track loan portfolio health. Key objectives included:  
- Monitoring loan repayment status and trends  
- Understanding borrowing patterns of online store owners  
- Supporting proactive, data-driven decision-making  
- Enabling stakeholders to interactively explore insights via **self-service dashboards**  

---

## Data Understanding & Processing
Data processing was performed in **Google BigQuery**, following **ETL best practices**:  

**Key Tasks Completed:**  
1. **Explore Fintech Dataset** – Reviewed customers and loans tables, schema, and sample data  
2. **Import CSV and Create Tables** – Added regional data using Cloud Storage  
3. **Join Tables & Create Derived Tables (CTAS)** – Combined loans and regional data into `loan_with_region`  
4. **Work with Nested Data** – Queried nested `purpose` column to create a clean `loan_purposes` table  
5. **Answer Business Questions** – Created `loan_count_by_year` table using `COUNT` and `GROUP BY`  

**Technical Concepts Applied:**  
- ETL pipelines for data ingestion and transformation  
- Star schema modeling for efficient querying  
- BigQuery SQL for data transformation, aggregation, and reporting  

---

## Dashboard & Visualizations
A **self-service dashboard** was built using **Looker Studio (Looker Enterprise)** to activate insights and enable interactive exploration.

**Key Visualizations:**  
1. **Total Outstanding Loan Amount** – Single-value KPI with conditional formatting  
2. **Percentage of Outstanding Loans by Status** – Pie chart for status distribution  
3. **Total Count of Outstanding Loans by State** – Bar chart of top 10 states  
4. **Top 10 Customers by Highest Income** – Table with filters on loan status and home ownership  

**Dashboard Features:**  
- Interactive, user-friendly layout with clear labeling  
- Automated refresh schedule (hourly/daily) for real-time insights  
- Accessible and optimized for stakeholders’ needs  

![Loan Dashboard](images/loan_dashboard.png)

---

## Key Outcomes / Insights
- Implemented **cloud-native ETL pipelines** to process large-scale loan data  
- Designed **star schema data model** for optimized queries and reporting  
- Enabled **self-service analytics** for interactive exploration by stakeholders  
- Provided **actionable insights** to monitor loan health and improve portfolio management  

---

## Technical Skills & Tools
- **Google BigQuery** – Data ingestion, processing, storage  
- **Looker Studio / Looker Enterprise** – Self-service dashboards and visualization  
- **SQL** – Querying, data transformation, and aggregation  
- **Python** (optional) – Supplementary analysis  
- **Cloud Concepts** – ETL pipelines, star schema, cloud-native analytics, self-service BI  

---

## How to View
1. Open the **dashboard screenshot** in the `images/` folder  
2. Review the **executive summary PDF** for methodology, queries, and recommendations  

---

## Conclusion
This capstone project demonstrates my ability to:  
- Apply **cloud-based analytics** to solve real-world fintech challenges  
- Transform raw data into **interactive, self-service dashboards**  
- Implement **ETL pipelines and star schema models**  
- Communicate insights confidently to stakeholders  

It reflects my **curiosity, eagerness to learn, and confidence** in building professional analytics solutions with cloud technologies.
