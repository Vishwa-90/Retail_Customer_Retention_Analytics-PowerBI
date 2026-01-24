🛒 Retail Customer Retention Analytics (Power BI)
📌 Project Overview

Customer retention is a critical challenge in the retail industry due to increasing competition and evolving customer expectations. This project focuses on building an end-to-end Customer Retention Analytics solution using Power BI to analyze customer churn, loyalty behavior, store performance, and customer lifetime value (CLV).

The project demonstrates data modeling, DAX-based analytics, and dashboard storytelling skills, designed specifically as a portfolio project for entry-level Data Analyst / Business Analyst roles.

🎯 Business Objective

The objective of this project is to:

Understand why customers churn

Identify high-value and at-risk customers

Evaluate the effectiveness of loyalty programs and promotions

Link store performance with customer retention

Enable data-driven retention strategies using interactive dashboards

🧰 Tools & Technologies

Power BI

Power Query (Data Transformation)

DAX (Measures & Calculations)

Data Modeling (Star Schema)

Data Visualization & Dashboard Design

📂 Dataset Description

The project integrates multiple retail datasets:

Customer Demographics – Age, gender, income group, region, membership details

Customer Transactions – Purchase history across stores

Store Locations – Store type, region, opening year

Loyalty Program – Loyalty tier, points earned and redeemed

Churn Labelled Customers – Churn flag based on last purchase behavior

🔄 Analytical Approach

Data Cleaning & Modeling

Removed duplicates and handled missing values using Power Query

Standardized data types and created derived columns

Built a relational data model connecting customers, transactions, stores, loyalty, and churn data

DAX-Based Metrics

Churn Rate

Repeat Purchase Rate

Purchase Frequency Tiers

Promotion Impact Metrics

Customer Lifetime Value (CLV)

Customer Segmentation

Churned vs Active customers

Low / Mid / High purchase frequency segments

Low / Medium / High CLV customers

📊 Key Analysis Performed

Churn & Retention Analysis
Churn rates analyzed across region, income group, store type, and loyalty tier.

Repeat Purchase Behavior
Customers segmented based on transaction frequency to identify loyal and disengaging customers.

Promotion & Loyalty Impact
Compared spending behavior with and without promotions and analyzed loyalty points utilization.

Store Performance vs Retention
Linked store type and region with churn and transaction value.

Customer Lifetime Value (CLV)
Identified high-value customers and high-value at-risk customers for targeted retention.

📈 Dashboard Structure

The Power BI report consists of multiple interactive pages:

Executive Overview – KPIs: Churn Rate, CLV, Repeat Rate

Loyalty & Promotion Analysis

Store & Regional Performance

Customer Segmentation

Slicers: Region, Income Group, Loyalty Tier, Store Type

💡 Key Insights & Recommendations

High churn observed in specific regions, store types, and loyalty tiers

Loyalty points are earned but underutilized, indicating weak engagement

High-value customers contribute a disproportionate share of revenue

Store-specific and segment-driven campaigns can significantly reduce churn

Business Recommendations:

Run targeted “Win Back” campaigns for churned customers by region/store

Improve loyalty point redemption strategies to boost engagement

Focus retention efforts on high-churn loyalty tiers and income groups

Design store-specific promotional strategies using historical performance data

📌 Business Impact

This project enables:

Proactive churn management

Better prioritization of high-value customers

Data-driven loyalty and promotional strategies

Improved decision-making through interactive dashboards

📁 Repository Structure
Retail-Customer-Retention-Analytics/
│
├── Dataset/
│   ├── Customer_Demographics.csv
│   ├── Customer_Transactions.csv
│   ├── Loyalty_Program.csv
│   ├── Store_Locations.csv
│   └── Churn_Labelled_Customers.csv
│
├── Dashboard/
│   ├── Retail_Customer_Retention.pbix
│   └── Dashboard_Screenshots/
│
├── Project_Report.pdf
├── README.md