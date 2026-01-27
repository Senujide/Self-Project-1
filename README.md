# Self-Project-1
Customer segmentation and sales analysis using Python and Power BI with interactive dashboards and business insights.

# Customer Segmentation & Sales Analysis
**Power BI and Python | Self Project**

---

## Project Overview
This self project focuses on analyzing retail transaction data to understand customer purchasing behavior and segment customers into meaningful groups. The project combines Python-based data analysis with Power BI dashboards to generate actionable business insights. The analysis helps identify repeat customers, high-value customers, and overall sales patterns that support data-driven decision making.

---

## Project Objectives
- Analyze customer purchase behavior using transactional data  
- Identify repeat and high-value customers  
- Segment customers based on sales and frequency patterns  
- Visualize insights using interactive Power BI dashboards  
- Support marketing and customer retention strategies  

---

## Dataset Description
The dataset used in this project contains retail transaction-level data such as:
- Customer ID  
- Transaction ID
- Total Purchases  
- Product Category 
- Payment Methods  

The raw dataset required cleaning and preprocessing before analysis.

---

##  Cleaning and Preprocessing
Data preparation was performed using Python in a Jupyter Notebook. The process included:
- Removing missing and invalid records  
- Creating derived variables such as average order value  
- Converting date fields for time-based analysis  
- Standardizing features for customer segmentation  

These steps ensured the dataset was suitable for analysis and modeling.

---

## Exploratory Data Analysis
Exploratory data analysis was conducted to:
- Understand sales trends over time  
- Analyze customer purchase frequency  
- Examine repeat customer behavior  
- Evaluate revenue contribution across customer groups  

Insights from this stage guided the selection of features used for customer segmentation.

---

## Customer Segmentation Methodology
Customer segmentation was performed using clustering techniques in Python.

### Features Used
- Age
- Total Sales  
- Purchase Frequency  
- Average Order Value  

After feature scaling, customers were grouped into distinct segments representing different purchasing behaviors such as high-value customers, loyal repeat customers, low spenders, and at-risk customers.

---

## Power BI Dashboard
An interactive Power BI dashboard was developed to visualize insights clearly and effectively.
Power BI (.pbix) files are stored using Git LFS due to GitHub file size limits.


### Dashboard Includes
- KPI Total Customers, Sales, Transatcions
- Repeat Customer Trend Analysis  
- Sales Trend Over The Time  
- Customer Segment Distribution
- Customer Satisfaction Analysis

### Drill-Through Analysis
- Dedicated drill-through page for customer clusters  
- Enables deeper analysis of individual customer behavior  

### Dashboard Screenshots
Dashboard screenshots are stored in the following paths:
![Dashboard Overview](screenshots/dashboard_overview.png)
![Customer Segmentation](screenshots/diagnostics_analysis.png)
![Drill Through Analysis](screenshots/drill_through_analysis.png)
  
---

## Key Insights
- A small percentage of customers contribute a large share of total revenue  
- Repeat customers contribute for majority of sales over time  
- Customer segmentation enables targeted marketing strategies  
- Identifying at-risk customers supports proactive retention efforts  

---

## Tools and Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib)  
- Jupyter Notebook  
- Power BI  
- GitHub  

---

## Repository Structure

Project1.ipynb
README.md
screenshots/dashboard_overview.png
screenshots/customer_segmentation.png
screenshots/drill_through_analysis.png


---

## How to Use the Project
- Open `Project1.ipynb` to review data cleaning, EDA, and customer segmentation steps  
- Open the Power BI dashboard file using Power BI Desktop  
- Use slicers and drill-through features to explore insights  
- Review dashboard screenshots directly from the screenshots folder  

---

## Future Improvements
- Incorporating RFM analysis for enhanced behavioral segmentation
- Including real-time data updates for dynamic dashboard monitoring
- Developing predictive churn models using supervised learning


---

## 👩‍💻 Author
**Senuji De Costa**  
Undergraduate at University of Moratuwa


