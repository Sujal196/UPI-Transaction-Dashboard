
# UPI-Transaction-Dashboard

### Dashboard Link : *(To be updated after Power BI Service publication)*

# Problem Statement

The rapid growth of **Unified Payments Interface (UPI)** has transformed digital payment ecosystems by enabling fast, secure and real-time financial transactions across banking platforms. With the increasing volume of transactions across multiple banks, devices and payment channels, organizations require advanced analytical tools to monitor transaction behavior, identify operational inefficiencies and optimize payment infrastructure.

The **UPI Transaction Dashboard** provides a comprehensive analytical view of digital payment activities by monitoring key metrics such as total transactions, transaction value, payment methods, transaction success rate, device usage and demographic distribution.

This dashboard converts raw transactional records into interactive business intelligence insights, allowing stakeholders to evaluate payment trends, analyze system performance, detect transaction failures and understand user behavior across different cities, age groups and device types.

Through interactive filtering and visual analytics, the report supports data-driven decision-making, operational monitoring and digital payment ecosystem optimization.

# Dataset Overview

The dataset used for this dashboard consists of structured UPI transaction records containing payment details, customer demographics, device information and transaction outcomes.

### Key attributes included in the dataset:

* Transaction ID
* Transaction Date
* Transaction Time
* Amount
* Bank Sent
* Bank Received
* Remaining Balance
* City
* Gender
* Customer Age
* Device Type
* Payment Method
* Payment Mode
* Transaction Type
* Transaction Status
* Currency
* Merchant Name
* Purpose

The data was imported into **Power BI Desktop**, transformed using **Power Query** and structured through proper data modeling to enable efficient analytics and high-performance visualizations.

# Steps Followed

## Data Preparation

* **Step 1:** Imported the UPI transaction dataset into **Power BI Desktop**.
* **Step 2:** Opened **Power Query Editor** to perform data cleaning and validation.
* **Step 3:** Enabled **Column Quality, Column Distribution, and Column Profile** to identify anomalies.
* **Step 4:** Enabled **column profiling for the entire dataset** instead of the default sample rows.
* **Step 5:** Corrected data types for fields such as Amount, Transaction Date and Customer Age.
* **Step 6:** Handled missing values and validated categorical fields like Payment Method and Device Type.
* **Step 7:** Created a **Month-Year column** to enable time-based trend analysis.

## Data Modeling

* **Step 8:** Structured the dataset in a **star schema format** for optimized reporting.
* **Step 9:** Created calculated measures using **DAX** for core metrics such as Total Transactions, Total Amount, Success Rate and Failure Rate.
* **Step 10:** Implemented calculated fields for **Age Groups** (Young Adults, Adults, Elders) to support demographic analysis.
* **Step 11:** Created a **sorting column for Month-Year** to ensure proper chronological ordering in time-based visuals.

## Visualization Development

* **Step 12:** Designed a professional dashboard layout using a **consistent UI theme and color palette** aligned with digital payment branding.
* **Step 13:** Added **KPI cards** to summarize total transactions, total transaction value, success rate and failure rate.
* **Step 14:** Implemented **interactive slicers** to filter transactions by payment method, transaction status, device type, city, transaction type and transaction date.
* **Step 15:** Created a **currency distribution pie chart** to analyze transaction value across multiple currencies.
* **Step 16:** Developed a **line chart visualization** to compare total amount by payment method.
* **Step 17:** Added a **donut chart** to analyze distribution between payment transfers and payments.
* **Step 18:** Designed a **Sankey-style flow visualization** to display transaction flow between sending and receiving banks.
* **Step 19:** Created a **scatter plot with play axis** to analyze the relationship between transaction amount and remaining balance across age groups over time.
* **Step 20:** Built a **transaction table visualization** containing detailed transactional records for granular analysis.

# Key Performance Indicators (KPIs)

The dashboard provides high-level summary metrics to help stakeholders quickly assess digital transaction performance.

### Total Transactions – **20K**

Represents the total number of UPI transactions processed within the dataset. This metric reflects the **overall transaction volume** handled by the payment ecosystem.

### Total Transaction Amount – **19.87M**

Indicates the total financial value transferred across all UPI transactions. This KPI measures **transaction throughput and payment system utilization**.

### Success Rate – **80%**

Shows the percentage of successfully completed transactions. A higher success rate indicates **efficient transaction processing and system reliability**.

### Failure Rate – **20%**

Represents the percentage of transactions that failed due to reasons such as network issues, insufficient balance or system errors. Monitoring this metric helps identify **payment infrastructure bottlenecks**.

# Dashboard Snapshot

## UPI Transaction Table View

![UPI Transaction Table](https://github.com/user-attachments/assets/d3e6ec82-d818-49e9-ab16-af9a79b7c2db)


## UPI Transaction Analytics Overview

![UPI Transaction Dashboard](https://github.com/user-attachments/assets/a9352052-d784-4734-898a-aece46eb0c70)

# Gender-based Transaction Analysis

The dashboard highlights transaction value distribution between male and female users.

### Female Users

**Total Transaction Amount:** 9,944,372.88

### Male Users

**Total Transaction Amount:** 9,927,901.15

The analysis shows a balanced transaction contribution between genders, indicating broad adoption of digital payments across demographics.

# Total Amount by Currency

A pie chart visualization illustrates transaction distribution across different currencies.

Currencies analyzed include:

* INR
* USD
* GBP
* EUR

Key insights:

* INR transactions represent the largest share of transaction value.
* International currencies indicate cross-border payment activity.
* Transaction value remains evenly distributed across currency categories.

This visualization helps stakeholders evaluate global transaction participation and currency utilization patterns.

# Total Amount by Payment Method

A line chart visualization compares the total transaction value across major payment methods:

* Phone Number
* QR Code
* UPI ID

### Key Observations

* UPI ID transactions contribute the highest total payment value.
* QR Code transactions show slightly lower transaction volume compared to other methods.
* Phone number payments maintain consistent usage across transactions.

This insight helps payment providers understand customer preference for payment authentication channels.

# Total Amount by Transaction Type

A donut chart visualization categorizes transaction value based on transaction type.

### Transaction Categories

* Transfer
* Payment

### Key Findings

* Transfers account for approximately 50% of the total transaction value.
* Payment-based transactions contribute nearly the remaining share.

This analysis highlights how users leverage UPI for both peer-to-peer transfers and merchant payments.

# Bank Transaction Flow Analysis

The dashboard includes a bank-to-bank transaction flow visualization showing how funds move between sending and receiving banks.

Banks included in the analysis:

* SBI Bank
* HDFC Bank
* ICICI Bank
* Axis Bank

### Insights

* Major transaction flows occur between large banking institutions.
* Transaction value appears balanced across sending and receiving banks.
* Banks with higher transaction throughput indicate stronger UPI network participation.

This visualization supports bank performance monitoring and payment infrastructure analysis.

# Transaction Behavior by Age Group

A scatter plot visualization analyzes the relationship between transaction amount and remaining account balance across different customer age groups over time.

Age groups included:

* Young Adults
* Adults
* Elders

### Observations

* Young adults exhibit higher transaction activity across months.
* Adult users maintain consistent transaction patterns.
* Elderly users demonstrate lower transaction frequency but moderate transaction value.

The play axis allows stakeholders to observe transaction behavior evolution over time, enabling dynamic trend analysis.

# Interactive Filters

The dashboard includes multiple slicers that allow users to explore the data dynamically.

### Available Filters

* Payment Method
* Transaction Status
* Device Type
* City
* Transaction Type
* Transaction Date

These filters allow analysts and decision-makers to drill down into specific transaction segments and perform targeted analysis.

# Key Business Insights

The dashboard reveals several important operational and strategic insights:

* The UPI ecosystem processed 20K transactions totaling 19.87M in value, demonstrating significant digital payment activity.
* Transaction success rate remains strong at 80%, though monitoring the 20% failure rate is critical for improving system reliability.
* UPI ID is the most frequently used payment method, indicating strong user preference for direct identifier-based payments.
* Transaction flows between major banks dominate the payment network, highlighting their role in facilitating digital transactions.
* Young adult users contribute a large share of transaction activity, reflecting high digital payment adoption among younger demographics.
* Transaction volumes remain distributed across multiple currencies, indicating potential cross-border transaction participation.

  
# Conclusion

The **UPI Transaction Power BI Dashboard** provides a powerful analytical platform for monitoring and understanding digital payment activity within the UPI ecosystem.

By integrating transaction data, payment methods, banking relationships, demographic analysis and system performance metrics, the dashboard enables organizations to:

* Monitor digital payment system performance.
* Identify transaction failures and operational inefficiencies.
* Understand customer payment behavior.
* Analyze banking network transaction flows.
* Improve digital payment infrastructure and user experience.

Overall, the dashboard supports data-driven strategic decision-making and financial transaction monitoring, making it an essential tool for organizations operating in the digital payments landscape.
