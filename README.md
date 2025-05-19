# Bank Loan Analysis and Dashboard Development

## Overview

The Bank Loan Analysis and Dashboard Development project provides comprehensive and actionable insights into bank loan portfolios through detailed analytics. This project enables enhanced understanding of lending activities, borrower behaviors, loan repayment performance, and risk profiles. The resulting dashboards offer banks clear, interactive visibility into key lending metrics, helping them make data-driven decisions, improve lending strategies, proactively manage risks, and maintain regulatory compliance.

## Purpose

The primary goal of this project was to deliver interactive, analytical dashboards that enable banks to thoroughly monitor and assess crucial loan-related metrics. These metrics include total loan applications, total funded amounts, loan repayments, average interest rates, and borrower Debt-to-Income (DTI) ratios. The dashboards also provide insights into the quality of loans by categorizing them into Good Loans (Fully Paid, Current) and Bad Loans (Charged Off), facilitating strategic planning and operational improvements.

## Problems Addressed

This project effectively addressed the need for:

* Clear visibility into loan metrics to support strategic decisions.
* Accurate tracking of borrower repayment patterns to manage risk.
* Comprehensive reporting capabilities for risk assessment and regulatory compliance.

## Technology Stack

* **SQL:** Employed for precise data extraction, detailed querying, and computation of critical metrics from large loan datasets.
* **Excel:** Utilized for initial data cleaning tasks, such as formatting cells, addressing NULL values, filtering irrelevant data, and conducting preliminary analyses.
* **Tableau:** Selected for creating highly interactive and intuitive dashboards to visualize data effectively for stakeholder analysis and reporting.

## Project Execution

### Step-by-Step Technical Process

1. **Domain Understanding and Requirements Analysis**

   * Reviewed detailed domain knowledge documentation on banking loan procedures, application processes, lending criteria, risk management strategies, regulatory compliance requirements, and loan categorization standards.

2. **Data Extraction and Detailed SQL Query Development**

   * Developed and executed advanced SQL queries, including:

     * Aggregation queries (COUNT, SUM, AVG) for calculating total applications, total funded amounts, and collected payments.
     * Conditional logic queries for distinguishing between Good Loans (Fully Paid, Current) and Bad Loans (Charged Off).
     * Comparative analysis queries for Month-to-Date (MTD) and Previous-Month-to-Date (PMTD) metrics.
     * Group-by queries to aggregate data based on loan attributes, including loan status, issue date, borrower state, loan term, employment length, loan purpose, and homeownership.

3. **Data Preparation and Analysis in Excel**

   * Imported SQL query results into Excel for further data refinement, including:

     * Formatting data cells to ensure consistency and readability.
     * Addressing NULL values by filling in or removing incomplete data entries.
     * Filtering and organizing data to highlight key patterns and anomalies.
   * Conducted exploratory data analysis to validate data accuracy and prepare it for visualization.

4. **Interactive Dashboard Development with Tableau**

   * Designed and built comprehensive dashboards in Tableau, presenting interactive visualizations such as:

     * Monthly trend analysis for loan applications, funding, and repayments using line charts.
     * Geographic visualization of loan metrics across states using filled maps.
     * Loan term distribution insights using donut charts.
     * Employment length analysis using bar charts.
     * Detailed purpose analysis to understand loan motivations using bar charts.
     * Homeownership impact evaluation using tree maps.

5. **Dashboard Validation and Interactive Filtering**

   * Implemented and rigorously tested dashboard filters to ensure precise and interactive data exploration.
   * Conducted validation checks to verify data accuracy, responsiveness, and consistency across all visualizations.

## Key Findings

* Detected significant seasonal fluctuations in loan applications, facilitating improved forecasting accuracy.
* Clearly identified loan quality through Good versus Bad loan categorization, enhancing risk assessment capabilities.
* Revealed borrower segmentation based on employment duration, homeownership status, and loan purpose, aiding targeted marketing strategies.
* Highlighted regional lending trends, enabling better strategic decisions in market expansions and resource allocations.

## Real-world Implications

This detailed analytics project equips banks to:

* Enhance credit risk management by proactively identifying and addressing potential loan default risks.
* Tailor loan offerings to specific borrower profiles, improving customer satisfaction and retention.
* Streamline regulatory compliance with efficient and accurate reporting processes.
* Drive strategic decision-making and sustainable growth through clear, actionable lending insights.
