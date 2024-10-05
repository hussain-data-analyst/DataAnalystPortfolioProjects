# Bank Loan Portfolio Assessment

## Project Overview

This project aims to create a comprehensive **Bank Loan Report** using SQL Server and Power BI. The report provides critical insights into the performance of our bank's loan portfolio, helping track key loan-related metrics, assess the health of our lending activities, and identify trends for data-driven decision-making.

## Key Objectives

The main goals of the project are:

*   **Monitor Lending Performance:** Track total loan applications, funded amounts, and amounts received.
*   **Distinguish Between Good and Bad Loans:** Separate loans based on their status (Fully Paid, Current, Charged Off) and analyze the quality of the loan portfolio.
*   **Provide Insights via Dashboards:** Create detailed Power BI dashboards to visualize loan trends, regional performance, loan term analysis, and more.

## Features in the Dataset

The dataset includes the following features:

*   **ID-related Fields:** `id`, `member_id`
*   **Loan Info:** `loan_status`, `loan_amount`, `int_rate`, `installment`, `term`
*   **Borrower Info:** `emp_length`, `emp_title`, `home_ownership`, `annual_income`, `dti`, `total_acc`
*   **Dates:** `issue_date`, `last_credit_pull_date`, `last_payment_date`, `next_payment_date`
*   **Other Fields:** `address_state`, `application_type`, `grade`, `sub_grade`, `verification_status`, `purpose`, `total_payment`

## Dashboards and KPIs

### 1. Dashboard 1: Summary

This dashboard provides an overview of key metrics:

*   **Total Loan Applications:** The total number of applications and Month-to-Date (MTD) comparisons.
*   **Total Funded Amount:** The total loan disbursements and Month-over-Month (MoM) analysis.
*   **Total Amount Received:** Tracking borrower repayments and MoM changes.
*   **Average Interest Rate:** Monitoring interest rates across loans.
*   **Average Debt-to-Income Ratio (DTI):** Evaluating borrowers’ financial health.

#### Good Loan vs. Bad Loan KPIs

*   **Good Loan Applications & Funded Amounts:** Includes 'Fully Paid' and 'Current' loans.
*   **Bad Loan Applications & Funded Amounts:** Loans categorized as 'Charged Off.'

### 2. Dashboard 2: Overview

This dashboard includes visual representations of key loan metrics:

*   **Monthly Trends (Line Chart):** Shows how total loan applications, funded amounts, and amounts received vary over time.
*   **Regional Analysis (Filled Map):** Visualizes loan activity by state.
*   **Loan Term Analysis (Donut Chart):** Breakdown of loans by different term lengths (e.g., 36 months, 60 months).
*   **Employment Length (Bar Chart):** Displays lending metrics based on borrowers’ employment history.
*   **Loan Purpose (Bar Chart):** Analyzes loan applications by purpose (e.g., debt consolidation, refinancing).
*   **Home Ownership (Tree Map):** Hierarchical view of loan metrics by home ownership status.

### 3. Dashboard 3: Details

A detailed view that provides a holistic snapshot of key loan-related metrics, giving users a one-stop interface for in-depth analysis of loan performance, borrower profiles, and more.

## Tools and Technologies Used

*   **SQL Server:** Used for data extraction and querying.
*   **Power BI:** Used for data visualization and creating interactive dashboards.

## How to Run the Project

1.  **SQL Queries:**
    *   Refer to the `SQL_Queries_and_Results.pdf` file in the `/Docs` folder. This PDF contains the SQL commands used for data extraction, along with screenshots of the outputs and explanations.
2.  **Power BI Dashboard:**
    *   Open the `.pbix` file in Power BI to view the interactive dashboards.
    *   Use filters to explore different aspects of the data (e.g., by state, loan term, loan status).

## Key Insights

*   **Total Loan Applications:** **38,576** applications received, with **4,314** processed in December 2021, showcasing strong demand.
*   **Total Funded Amount:** **$435.76 million** disbursed, including **$53.98 million** in December, demonstrating effective funding capabilities.
*   **Total Amount Received:** A robust **$473.07 million** collected overall, with **$58.07 million** received this month, highlighting effective repayment strategies.
*   **Average Interest Rate:** **12.05%** with a Month-to-Date (MTD) average of **12.36%**.
*   **Average Debt-to-Income Ratio (DTI):** **13.33%** (MTD: **13.67%**), indicating borrowers' financial health.
*   **Good Loan Percentage:** **86%** (33,243 applications), with **$370.22 million** funded and **$435.79 million** received.
*   **Bad Loan Percentage:** **13.82%** (5,333 applications), with **$65.53 million** funded and **$37.28 million** received.

In summary, this report highlights our strengths while uncovering areas for improvement in our lending practices.
