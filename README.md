Marketing Campaign Performance Optimization

Project Overview

This project analyzes **Google Ads marketing campaign data** to evaluate campaign performance, identify optimization opportunities, and generate actionable business insights.The goal of this project is to simulate a real-world marketing analytics workflow, including data cleaning, KPI calculation, exploratory data analysis, and dashboard development using Python and Power BI.

Business Objective

Marketing teams need to understand which campaigns, keywords, devices, and locations generate the highest return on investment.

This project answers key questions such as:

* Which marketing campaigns generate the highest revenue?
* Which keywords drive the most conversions?
* Which device performs best for ad engagement?
* How efficient are campaigns in terms of customer acquisition cost?

Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Power BI
* GitHub

Project Structure
marketing-optimization-project
│
├── data
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks
│   └── marketing_analysis.ipynb
│
├── powerbi
│   └── marketing_dashboard.pbix
│
├── images
│   └── dashboard_preview.png
│
└── README.md

 Data Cleaning

The raw dataset contained several real-world data quality issues:

* Spelling mistakes in Campaign_Name
* Missing values
* Duplicate records
* Numeric columns stored as text
* Inconsistent text formatting

Cleaning Steps

1. Standardized text formatting
2. Corrected spelling mistakes in campaign names
3. Converted numeric columns from object → numeric
4. Removed duplicates
5. Handled missing values
6. Created calculated marketing KPIs

Marketing KPIs Created

Key performance metrics were calculated for campaign evaluation:

Click Through Rate (CTR)
CTR = Clicks / Impressions

Cost Per Acquisition (CPA)
CPA = Cost / Conversions

Return on Ad Spend (ROAS)
ROAS = Revenue / Cost

These KPIs help measure campaign efficiency and marketing ROI.

Exploratory Data Analysis

The following analyses were performed:

* Campaign revenue comparison
* Device performance analysis
* Geographic revenue analysis
* Keyword performance evaluation
* Marketing funnel analysis
* Cost vs revenue efficiency analysis

-Power BI Dashboard

A Power BI dashboard was created to visualize marketing performance.

Dashboard Features

Marketing Overview

* Total Revenue
* Total Cost
* Total Conversions
* ROAS KPI

Campaign Analysis

* Revenue by campaign
* CPA by campaign
* CTR by campaign

Audience Insights

* Device performance
* Location revenue
* Top performing keywords

Key Insights

Some insights discovered during the analysis:

* Certain campaigns generated significantly higher revenue
* Mobile users contributed the highest number of conversions
* A small set of keywords drove most conversions
* Some campaigns had higher CPA, indicating inefficient ad spend

These insights can help marketing teams optimize budget allocation and improve ROI.

Future Improvements

* Conversion prediction using machine learning
* Marketing budget optimization model
* A/B testing analysis
* Automated campaign performance monitoring

Project Purpose

This project was created as a portfolio project for learning and demonstrating marketing analytics skills, including data cleaning, KPI analysis, and dashboard development.

The dataset intentionally contains spelling mistakes, inconsistent formatting, and missing values to simulate real-world marketing data. Data cleaning and preprocessing were performed using Python before building the Power BI dashboard.

Author
Bhranti Patel - Data Analyst 
(Founder of OptiMerce AI )
