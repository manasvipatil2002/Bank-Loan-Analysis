# Bank Loan Report



📌 Key Insights & Analysis
Some major takeaways from the Power BI dashboard:

Loan Approval Trends: Highest approval rates seen in applicants with steady employment and higher incomes.

Default Analysis: Defaults were more frequent among self-employed individuals and lower-income brackets.

Demographics & Loan Behavior:

Younger age groups (20–30) had higher application rates.

Married applicants had a higher chance of loan approval.

Loan Amount & Term Trends:

Longer loan terms had higher default risks.

Median loan amount skewed higher for urban applicants.

🎯 Project Motivation
With increasing non-performing assets in the banking sector, there’s a need for data-driven lending decisions. This project was created to:

Explore which factors influence loan approval and default.

Empower banks to create risk profiles for applicants.

Help develop targeted marketing strategies for loan products.

🛠️ Technology Stack
Power BI Desktop – Data visualization and dashboard creation

Power Query – Data cleaning and transformation

DAX (Data Analysis Expressions) – Custom calculations and KPIs

Excel/CSV Files – Initial data source (if applicable)






##  🧠 Project Overview
 This Power BI project provides an analytical overview of bank loan data, aiming to extract actionable insights about loan approvals, defaults, and customer demographics. The report supports decision-makers in identifying key trends and potential risk factors, enabling better lending strategies.This report aims to provide stakeholders with actionable insights into loan applications, approvals, and related metrics.

 ## 🧹 Data Cleaning & Preparation
Before creating visualizations, the dataset underwent several cleaning and preprocessing steps:
- Handled Missing Values: Rows with critical missing fields were removed or imputed.

- Data Type Corrections: Ensured consistent formats for date, numerical, and categorical columns.

- Feature Engineering: Added calculated columns such as:

- Loan Approval Rate

- Default Status Indicator

- Income-to-Loan Ratio

- Removed Duplicates: Ensured each record represented a unique loan applicant.


## Data Source
The loan data for this project is sourced from an internal banking database, capturing comprehensive information about the bank's lending activities
[data source](https://docs.google.com/spreadsheets/d/1-1Ldoe-DwZTL77tdMtRgZAIzeAzs0jh3/edit?usp=sharing&ouid=116890999875311477003&rtpof=true&sd=true).


## Tools
- **SQL:** The project leverages SQL queries to retrieve, process, and analyze data database.
- **Tableau:** Dynamic and interactive visualizations are crafted in Tableau to present key findings effectively.


## Dashboards
### Dashboard 1: Summary


!['Summary image'](/Images/Summary.png)

The Summary Dashboard captures key loan-related metrics and their changes over time, providing a snapshot of the loan portfolio's health and lending strategy impact. It includes the following KPIs:
- Total Loan Applications (MTD and MoM)
- Total Funded Amount (MTD and MoM)
- Total Amount Received (MTD and MoM)
- Average Interest Rate (MTD and MoM)
- Average Debt-to-Income Ratio (DTI) (MTD and MoM)

Additionally, it distinguishes between 'Good Loans' and 'Bad Loans,' with specific indicators for each category, helping in the assessment of loan portfolio quality.


### Dashboard 2: Overview

!['Overview image'](/Images/Overview.png)

The Overview Dashboard visually represents various loan-related metrics through different chart types:
- Monthly Trends by Issue Date 
- Regional Analysis by State 
- Loan Term Analysis 
- Employment Length Analysis 
- Loan Purpose Breakdown
- Home Ownership Analysis 

These visualizations aid in identifying trends, seasonal patterns, and the distribution of loans across various categories.

### Dashboard 3: Details

!['Details image'](/Images/Details.png)

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

## Implementation
The project required importing the dataset from Excel into SQL Server for analysis and visualization using Tableau. Dashboards were crafted using Tableau's powerful visualization tools and analytical capabilities, aligning with the specified requirements in the problem statement and utilizing the data dictionary to ensure precise field utilization.

## Data Validation
To ensure the accuracy and integrity of the data reflected in the dashboards, a thorough data validation process was undertaken. After the dataset was loaded into Tableau and from SQL Server database, the following measures were implemented:
- SQL Query Verification: Direct queries were executed against the SQL Server database to retrieve raw data. This dataset served as a benchmark, validating the accuracy and consistency of the information presented in the dashboards.

- Data Consistency Checks: The results from Tableau were compared against the SQL query results to ensure consistency. This step was critical to confirm that the data transformation and logic applied within Tableau did not alter the actual figures.

- KPI Logic Validation: The calculations and logic underlying the Key Performance Indicators (KPIs) were thoroughly reviewed. SQL scripts were employed to independently replicate the KPI calculations, ensuring the accuracy and reliability of the computations performed in Tableau.


- Cross-Verification with Source Data: The transformed data in Tableau was cross-verified with the source data from the SQL Server database. This step was crucial to confirm that all data transformations, including filtering, grouping, and aggregation, were correctly applied.


Through these validation steps, the project ensured that the Tableau dashboards accurately represent the data, and the insights derived are based on truthful and unaltered information. This rigorous validation process enhances the credibility of the dashboards and reinforces confidence in the data-driven decisions made using these tools.

## Conclusion
By incorporating robust data validation techniques, the Bank Loan Dashboard project establishes itself as a reliable and authoritative source for monitoring the bank’s loan activities. The project not only presents critical data through intuitive visualizations but also guarantees the precision of the information displayed, enabling the bank to make informed and assured strategic decisions with confidence.
