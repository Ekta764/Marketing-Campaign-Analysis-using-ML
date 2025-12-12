**Marketing Campaign Response Analysis**

This project analyzes a retail marketing dataset to understand customer behavior, identify key predictors of campaign acceptance, and recommend targeted marketing strategies.
All analysis was performed using Microsoft Excel’s Data Science tools, including data cleaning, transformations, pivot tables, correlations, regression output, and visual analytics.

 **Project Overview**

The goal of this project is to predict whether a customer will accept a new marketing campaign, and to understand which customer characteristics, behaviors, and spending patterns influence campaign response.

This includes:

Exploring customer demographics

Understanding product category spending

Examining engagement behavior (recency, purchases, web visits)

Analyzing past campaign acceptance

Building predictive insights using Excel’s Data Science tab

The final findings were summarized in a Machine Learning Final Presentation (included in this repository).

**Dataset Summary**

The dataset contains 2,240 customers and 29 variables, including:

Demographics

Age

Income

Family composition (Kidhome, Teenhome)

Spending Behavior (last 2 years)

MntWines

MntMeatProducts

MntFruits

MntFishProducts

MntSweetProducts

MntGoldProds

TotalMnt (engineered total spend)

Engagement

Recency (days since last purchase)

Web visits

Store, catalog, and online purchases

Complaints

Campaign History (past 5 years)

AcceptedCmp1–AcceptedCmp5

AcceptedCampaigns (engineered total accepted)

**Data Cleaning & Feature Engineering**

Performed in Excel:

Fixed inconsistent data formats

Filled missing values

Corrected invalid birth years

Created TotalMnt (total spend across all product categories)

Created AcceptedCampaigns (sum of all 5 past campaigns)

Created TotalPurchases (sum across purchase channels)

**Analysis Performed (Excel Data Science Tools)**

Descriptive statistics

Correlation analysis

Pivot tables for customer segmentation

Histograms & boxplots

Logistic regression output

Decision tree (Excel add-in)

Classification metrics

Response probability analysis

🌟 Key Insights

Logistic Regression achieved the best performance (AUC ≈ 0.87).

Strong predictors of campaign acceptance include:

Lower Recency (recent shoppers)

Higher TotalMnt (high spenders)

Past campaign acceptance (AcceptedCampaigns)

Web and catalog engagement

Teenhome households are less responsive.

Income is not a meaningful predictor.

High-value customers show strong cross-selling potential.

**Final Recommendations**

Target customers with probability ≥ 0.25.

Prioritize active, high-spending customers.

Use catalog + web channels for promotions.

Focus on customers with a history of accepting campaigns.

**Repository Contents**
/analysis
    └── Marketing Campaign Analysis using Machine Learning.pdf

/excel_analysis_screenshots
    └── (screenshots of pivot tables, charts, correlations, regression output, etc.)


