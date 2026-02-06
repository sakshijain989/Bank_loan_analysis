# 🏦 Bank Loan Analysis & Risk Assessment Dashboard

## 📊 Project Overview
This project involves analyzing a dataset of **38,000+ loan records** to assess bank lending performance and credit risk. By utilizing **SQL (MySQL)** for backend data processing and **Power BI** for frontend visualization, the project delivers actionable insights into loan applications, funded amounts, and borrower financial health.

The goal is to help stakeholders monitor lending operations, identify "Bad Loan" risks, and track Month-over-Month (MoM) growth metrics.

## 🛠️ Tech Stack
* **Database:** MySQL (Data Cleaning, Analysis, Validation)
* **Visualization:** Microsoft Power BI (Dashboarding, DAX)
* **Data Processing:** Excel, Power Query
* **Techniques:** ETL, Data Modeling, Time Intelligence, KPI Tracking

## 🔍 Key Features

### 1. SQL Data Analysis
* **Data Cleaning:** Converted raw text dates to standard `DATE` format using `STR_TO_DATE`.
* **KPI Calculation:** Queries written to calculate Total Applications, Funded Amount, and Avg Interest Rate.
* **Validation:** Cross-verified SQL results with Power BI metrics to ensure **100% data accuracy**.
* **Categorization:** Logic implemented to distinguish between 'Good Loans' (Fully Paid) and 'Bad Loans' (Charged Off).

### 2. Power BI Dashboard (3 Pages)
* **Summary Page:** High-level KPIs (MTD & MoM tracking) and Good vs. Bad Loan segmentation.
* **Overview Page:** Visual trends by State (Map), Loan Purpose (Bar Chart), and Seasonality (Line Chart).
* **Details Page:** Granular grid view for deep-dive analysis into individual borrower profiles.

## 📈 Key Insights & Metrics
* **Total Funded Amount:** Analyzed over **$435M** in disbursed loans.
* **Risk Analysis:** Identified a **13% Bad Loan rate**, highlighting areas for stricter credit assessment.
* **Interest Trends:** Tracked fluctuations in Average Interest Rates to optimize lending strategies.
* **Borrower Health:** Monitored Average **DTI (Debt-to-Income)** ratios to gauge repayment capacity.

