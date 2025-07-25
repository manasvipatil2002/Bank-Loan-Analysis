## Bank Loan Report  



##  🧠 Project Overview
 This Power BI project provides an analytical overview of bank loan data, aiming to extract actionable insights about loan approvals, defaults, and customer demographics. The report supports decision-makers in identifying key trends and potential risk factors, enabling better lending strategies.This report aims to provide stakeholders with actionable insights into loan applications, approvals, and related metrics.

 <img src="image/6.png" width=1000 height = 500>

 ## 🧹 Data Cleaning & Preparation
Before creating visualizations, the dataset underwent several cleaning and preprocessing steps:
- Handled Missing Values: Rows with critical missing fields were removed or imputed.

- Data Type Corrections: Ensured consistent formats for date, numerical, and categorical columns.

- Feature Engineering: Added calculated columns such as:

- Loan Approval Rate

- Default Status Indicator

- Income-to-Loan Ratio

- Removed Duplicates: Ensured each record represented a unique loan applicant.

 ## 📌 Key Insights & Analysis
Some major takeaways from the Power BI dashboard:

**- Loan Approval Trends:** Highest approval rates seen in applicants with steady employment and higher incomes.

**- Default Analysis**: Defaults were more frequent among self-employed individuals and lower-income brackets.

**- Demographics & Loan Behavior:** 

Younger age groups (20–30) had higher application rates.

Married applicants had a higher chance of loan approval.

**- Loan Amount & Term Trends:**

Longer loan terms had higher default risks.

Median loan amount skewed higher for urban applicants.



## 🎯 Project Motivation
With increasing non-performing assets in the banking sector, there’s a need for data-driven lending decisions. This project was created to:

- Explore which factors influence loan approval and default.

- Empower banks to create risk profiles for applicants.

- Help develop targeted marketing strategies for loan products.



## 🛠️ Technology Stack
- Power BI Desktop – Data visualization and dashboard creation

- Power Query – Data cleaning and transformation

- DAX (Data Analysis Expressions) – Custom calculations and KPIs

- Excel/CSV Files – Initial data source (if applicable)



## Dashboards
### Dashboard 1: Summary

<img src="image/1.JPG" width=1000>


The Summary Dashboard captures key loan-related metrics and their changes over time, providing a snapshot of the loan portfolio's health and lending strategy impact. It includes the following KPIs:
- Total Loan Applications (MTD and MoM)
- Total Funded Amount (MTD and MoM)
- Total Amount Received (MTD and MoM)
- Average Interest Rate (MTD and MoM)
- Average Debt-to-Income Ratio (DTI) (MTD and MoM)

Additionally, it distinguishes between 'Good Loans' and 'Bad Loans,' with specific indicators for each category, helping in the assessment of loan portfolio quality.


### Dashboard 2: Overview

<img src="image/2.JPG" width=1000>

The Overview Dashboard visually represents various loan-related metrics through different chart types:
- Monthly Trends by Issue Date 
- Regional Analysis by State 
- Loan Term Analysis 
- Employment Length Analysis 
- Loan Purpose Breakdown
- Home Ownership Analysis 

These visualizations aid in identifying trends, seasonal patterns, and the distribution of loans across various categories.

### Dashboard 3: Details

<img src="image/3.JPG" width=1000>

The Details Dashboard offers a detailed view of the loan data, providing a comprehensive and user-friendly interface for accessing vital loan metrics, borrower profiles, and performance data.

#### Data Fields and Usage
The data utilized in the dashboards comprise several fields, each serving a specific purpose in loan management and risk assessment:

- Loan ID: Unique identifier for loans.
- Address State: Borrower location for regional analysis.
- Employment Length: Indicates - employment stability.
- Employee Title: Job title for income source verification.
- Grade/Sub Grade: Creditworthiness and risk classification.
- Home Ownership: Housing status for financial stability assessment.
- Issue Date: Loan origination date.
- Loan Status: Current state of the loan for performance tracking.
- Purpose: Loan reason for segmentation and customization.
- Term: Loan duration.
- Verification Status: Status of financial information verification.
- Annual Income: Yearly earnings for creditworthiness.
- DTI: Debt burden relative to income.
- Instalment: Monthly repayment amount.
- Interest Rate: Cost of borrowing.
- Loan Amount: Principal amount borrowed.

Each field plays a crucial role in managing loans, assessing borrower risk, structuring loan terms, and making informed lending decisions.


## Conclusion
By incorporating robust data validation techniques, the Bank Loan Dashboard project establishes itself as a reliable and authoritative source for monitoring the bank’s loan activities. The project not only presents critical data through intuitive visualizations but also guarantees the precision of the information displayed, enabling the bank to make informed and assured strategic decisions with confidence.
