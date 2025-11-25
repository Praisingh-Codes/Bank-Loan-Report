## Bank Loan Analytics Report – Interactive Excel Dashboard

A fully interactive Excel-based analytics system designed to help financial institutions monitor loan applications, funded amounts, repayments, borrower profiles, interest rates, and risk segmentation.

This project integrates data cleaning, processing, KPI modeling, advanced Excel formulas, and dashboard visualizations into a single, dynamic reporting solution.


#### Project Structure

Bank Loan Report/

├── Data/                          # Raw and cleaned loan datasets

│   ├── financial_loan.xlsx

│   └── financial_loan_data_excel.xlsx

├── Outcomes/                      # Dashboard output images

│   ├── bank loan overview dashboard outcome.png

│   └── bank loan summary dashboard outcome.png

├── Resources/                     # Logo and UI assets

│   └── Bank Logo.png

└── Bank Loan Analytics Report.xlsx   # Main Excel dashboard workbook


#### Dashboard Previews

📊 Overview Dashboard

![Overview Dashboard](Outcomes/bank%20loan%20overview%20dashboard%20outcome.png)

📋 Summary Dashboard

![Summary Dashboard](Outcomes/bank%20loan%20summary%20dashboard%20outcome.png)


#### Project Objectives

The bank required a reporting system capable of answering these key questions:

✔️ How many loan applications were received each month?

✔️ What is the total funded amount vs. amount received?

✔️ What is the average interest rate & debt-to-income ratio?

✔️ How many loans are Good vs. Bad?

✔️ Which states, purposes, and borrower profiles dominate loan activity?

✔️ How does loan performance vary across terms, employment length, and home ownership?

This project delivers a zero-maintenance, fully automated Excel reporting solution with slicers, interactive charts, and KPI blocks.


#### Key Features

🧮 KPI Modeling

The dashboard automatically calculates:

Portfolio-Level KPIs

- Total Loan Applications

- Total Funded Amount

- Total Amount Received

- Average Interest Rate

- Average Debt-to-Income Ratio (DTI)

- Month-to-Date (MTD) Metrics

- Month-over-Month (MoM %) Variations

Good Loan KPIs

(Fully Paid + Current)

- Application %

- Total Applications

- Funded Amount

- Amount Received

Bad Loan KPIs

(Charged Off)

- Application %

- Total Applications

- Funded Amount

- Amount Received

🧹 Data Cleaning

Includes complete preprocessing of loan records:

- Formatted dates & numeric fields

- Removed duplicates

- Standardized categorical values (purpose, grade, state)

- Validated missing amounts & corrected inconsistencies

- Ensured clean values for interest rate & DTI calculations

🔄 Data Processing

Data was transformed using:

- Pivot Tables

- Grouping by Month / Quarter / Year

- Calculated Fields for KPIs

- Loan term & employment length segmentation

Derived metrics:

  - MTD Loan Applications

  - MoM % Change

  - Good vs Bad loan distribution

📈 Data Analysis

-- Descriptive Statistics

Loan distribution across states, terms, and home ownership

Funding vs. repayment gaps

Borrower income patterns through DTI

Interest rate variation across grades and employment lengths

-- Loan Quality Assessment

Good Loan % = 86.18%

Bad Loan % = 13.82%

Identified risk concentration areas using loan status dashboards

📊 Interactive Dashboards

The Excel report contains three fully interactive dashboards:

#### Dashboard 1: Summary

Contains:

- Total Applications

- Funded Amount, Amount Received

- Good vs Bad Loan donut charts

- Status-wise grid table

- KPI cards with MTD + MoM updates

- Slicers for Grade & Purpose

#### Dashboard 2: Overview

Visualizations include:

- Monthly Trends (Applications, Funding, Received)

- State Map (Total Loan Applications by state)

- Term-Based Donut Chart

- Employment Length Bar Chart

- Loan Purpose Distribution

- Home Ownership Treemap

#### Dashboard 3: Details

A complete data exploration dashboard:

- Full record-level loan table

- Borrower details

- Slicers for purpose, state, grade, term, home ownership

- Direct lookup for investigation & audits


#### Insights & Recommendations

1️⃣ High performing loan categories

Debt consolidation & credit card loans dominate — offering stable repayment patterns.

2️⃣ State-wise variations

Certain regions exhibit higher NPA (bad loan) rates → useful for risk-based pricing.

3️⃣ Loan term impact

36-month loans show healthier repayment behavior.

4️⃣ Employment length correlation

Borrowers with 10+ years employment show the strongest repayment performance.

5️⃣ Home ownership effect

Mortgage & Rent groups behave differently → helps diversify lending strategies.


#### Tech Stack

- Microsoft Excel

- Pivot Tables / Pivot Charts

- Data Modeling

- Interactive Slicers

- Conditional Formatting

- Advanced Excel Formulas (SUMIFS, AVERAGEIFS, COUNTIFS, IF, DATE Functions)

- Maps, Donut Charts, Treemaps

- Excel Navigation Buttons


#### How to Use

1. Download the project folder

2. Open Bank Loan Analytics Report.xlsx

3. Enable Editing + Enable Macros (if prompted)

4. Navigate using the left sidebar buttons

5. Use slicers (Grade, Purpose, State, Term, Home Ownership)

6. Explore KPIs → Trends → Details


#### Contributions

Pull requests and suggestions are welcome!

If you'd like to enhance the dashboards or add more automation, feel free to contribute.
