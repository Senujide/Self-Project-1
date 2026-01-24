# Self-Project-1
Customer segmentation and sales analysis using Python and Power BI with interactive dashboards and business insights.
📊 Customer Segmentation & Sales Analysis

(Power BI & Python – Self Project)

📌 Project Overview

This self-project focuses on analyzing retail transaction data to understand customer purchasing behavior and segment customers into meaningful groups. The project combines Python-based data analysis and modeling with Power BI visual analytics to generate actionable business insights.

The final outcome is an interactive Power BI dashboard supported by a Python notebook that handles data preprocessing, exploratory analysis, and customer segmentation.

🎯 Project Objectives

The main objectives of this project are to:

Analyze customer purchasing patterns using transactional data

Identify repeat and high-value customers

Segment customers based on behavior and value

Visualize insights using interactive Power BI dashboards

Support data-driven decision-making for marketing and customer retention strategies

📂 Dataset Description

The dataset used in this project contains retail transaction-level data, including:

Customer ID

Invoice details

Product quantities

Unit prices

Transaction dates

Sales values

The raw dataset required cleaning and transformation before analysis.

🧹 Data Cleaning & Preprocessing (Python)

All data preparation steps were carried out in Project1.ipynb, including:

Removal of missing and invalid records

Filtering out cancelled or negative transactions

Creation of derived variables such as:

Total Sales

Purchase Frequency

Customer-level aggregations

Date transformation for time-based analysis

Standardization of features for modeling

These steps ensured the dataset was suitable for analysis and clustering.

📈 Exploratory Data Analysis (EDA)

EDA was conducted to understand:

Sales trends over time

Distribution of customer purchases

Frequency of repeat customers

Contribution of high-value customers to total revenue

Visual and statistical summaries helped guide feature selection for customer segmentation.

🧠 Customer Segmentation Approach

Customer segmentation was performed using clustering techniques in Python.

Key features used:

Total Sales

Purchase Frequency

Average Order Value

Methodology:

Feature scaling

Application of clustering algorithm

Interpretation and labeling of customer segments

Each cluster represents a distinct customer behavior group, such as:

High-value customers

Loyal repeat customers

Low-spending customers

At-risk customers

These segments were later visualized in Power BI.

📊 Power BI Dashboard Explanation

The Power BI dashboard was designed to provide clear, interactive insights for business users.

🔹 Main Dashboard Includes:

Total Sales KPI

Number of Customers

Repeat Customer Trends

Sales Over Time

Customer Segment Distribution

🔹 Drill-Through Analysis:

A dedicated drill-through page allows deeper analysis of customer clusters

Enables users to explore customer-level behavior within each segment

🔹 Interactivity Features:

Slicers for time period and customer segments

Dynamic visuals that respond to filters

Clean and minimal layout for easy interpretation

📸 Dashboard screenshots are available in the /screenshots folder.

🔍 Key Insights & Findings

A small percentage of customers contribute a large share of total revenue

Repeat customers show stable purchasing behavior over time

Customer segmentation helps identify high-value and at-risk customers

Targeted strategies can improve customer retention and sales growth

🛠 Tools & Technologies Used

Python (Pandas, NumPy, Scikit-learn, Matplotlib)

Jupyter Notebook

Power BI

GitHub for version control and documentation

📁 Repository Structure
├── Project1.ipynb                 # Data cleaning, EDA & modeling
├── README.md                      # Project documentation
├── screenshots/                   # Power BI dashboard screenshots
│   ├── dashboard_overview.png
│   ├── customer_segmentation.png
│   └── drill_through_analysis.png

▶️ How to View the Dashboard

Download the Power BI .pbix file (if shared)

Open it using Power BI Desktop

Use slicers and drill-through features to explore insights

Alternatively, review dashboard screenshots in the screenshots folder.

🚀 Future Enhancements

Add predictive models for customer churn

Automate data refresh and dashboard updates

Incorporate demographic or geographic data

Deploy dashboard via Power BI Service

📝 Author

Senuji
Undergraduate – Business Science
Self Project focused on Data Analytics & Business Intellig
