# Health Insurance Claims Analytics Dashboard

## Project Overview

Healthcare organizations and health insurance providers face increasing pressure to control rising claims costs while maintaining quality healthcare delivery. Identifying the key drivers of healthcare expenditure, understanding member risk profiles, and recognizing high-cost populations are essential for informed decision-making and sustainable healthcare financing.

This project analyzes a health insurance claims dataset using Power BI to uncover the demographic, behavioral, and regional factors influencing insurance claim costs. The dashboard provides executives with actionable insights into claims expenditure, risk concentration, and healthcare cost drivers through an interactive, business-focused reporting solution.

## Business Problem
1. What factors are driving high healthcare claims?
2. Which members are responsible for the largest proportion of claims expenditure?
3. How does smoking influence healthcare costs?
4. Which demographic groups incur the highest medical expenses?
5. Which geographical regions generate the highest claims costs?
6. How concentrated are healthcare costs among high-risk members?

Without these insights, organizations may experience:
* Increasing healthcare expenditure
* Inefficient risk management
* Poor resource allocation
* Limited ability to design preventive healthcare programs
* Reduced profitability and sustainability

# Project Objectives
* Identify the major drivers of healthcare claims costs.
* Segment members into Low-Medium Risk, and High-Risk cohorts.
* Compare healthcare costs across demographic groups.
* Evaluate the financial impact of smoking on healthcare expenditure.
* Analyze claims distribution across different geographical regions.
* Identify the concentration of claims among high-cost members.
* Develop an executive dashboard to support evidence-based decision-making.

# Dataset
**Source** Kaggle – Medical Cost Personal Dataset

**Dataset Characteristics**
* 1,338 insured members
* Individual-level healthcare insurance information
* Cross-sectional dataset (no historical claim dates)

**Key Variables**
* Age
* Sex
* BMI
* Number of Children
* Smoker Status
* Region
* Insurance Cost
  
# Tools Used
* Power BI Desktop
* Power Query
* DAX
* Data Modeling
* PowerPoint(For Dashboard wireframing) 

# Data Preparation
I took the following steps to prepare my data for analysis:
* Data quality assessment
* Data type validation
* Creation of BMI Categories
* Creation of Age Groups
* Creation of Risk Cohorts
* Development of calculated measures using DAX
* Interactive slicers and drill-down functionality
* Dashboard optimization and formatting

# Dashboard Pages
## 1. Executive Summary
This segment provides an executive overview of healthcare claims performance.

### Key KPIs
* Total Claims Cost
* Average Claim Cost
* High-Cost Member Percentage
* Smoker Cost Ratio

### Visualizations
* Claims Cost by Region
* Claims Cost by Risk Segment
* Average Claim Cost by Age Group

Purpose: Provide executives with a concise overview of portfolio performance and healthcare cost distribution.

## 2. Cost Driver Analysis
This segment Identifies the major factors influencing healthcare claims.

### Visualizations
* Average Claim Cost (Smokers vs Non-Smokers)
* Insurance Cost by BMI Category
* Age vs Insurance Cost (Scatter Plot)
* Claims Cost by Region
* Average Claim Cost by Gender

Purpose: Understand the variables contributing most significantly to healthcare expenditure.

## 3. Risk Segmentation
This segment analyzes the risk member concentration.

### Visualizations
* Claims Cost by Risk Cohort
* Risk Cohort Distribution by Region
* High-Risk Members by Age Group
* Top 10% High-Cost Members

Purpose: Support proactive risk management and identify populations requiring targeted interventions.

## 4. Business Insights & Recommendations
This page summarizes the key findings and provides actionable recommendations for healthcare decision-makers.

# Business Questions Answered
This dashboard answers the following business questions:
1. Which demographic group incurs the highest healthcare costs?
2. How much more expensive are smokers compared to non-smokers?
3. Which regions contribute the highest healthcare expenditure?
4. What proportion of members are classified as high-cost?
5. How concentrated are healthcare costs among high-risk members?
6. Which age groups should be prioritized for preventive healthcare interventions?
7. Which factors contribute most significantly to rising insurance costs?

# Key Insights
* Healthcare costs are highly concentrated among High-Risk members, indicating that a relatively small segment of the insured population accounts for a substantial share of total claims expenditure.
* Smoking remains one of the strongest predictors of increased healthcare costs, with smokers generating significantly higher average claims than non-smokers.
* Claims costs vary across geographical regions, suggesting opportunities for region-specific healthcare planning and resource allocation.
* Middle-aged and older adults generally incur higher average healthcare costs than younger members, highlighting the importance of age-targeted preventive care.
* Risk segmentation provides a practical framework for identifying members who may benefit from early intervention and disease management programs.

# Business Recommendations
The following recommendations are proposed:
1. Strengthen Preventive Care Programs: Develop targeted wellness and preventive healthcare initiatives for high-risk and high-cost populations to reduce future claims.
2. Implement Risk-Based Care Management: Use risk segmentation to identify members requiring proactive monitoring and personalized healthcare interventions.
3. Promote Smoking Cessation Programs: Invest in smoking cessation initiatives to reduce long-term healthcare costs and improve member health outcomes.
4. Optimize Regional Resource Allocation: Allocate healthcare resources based on regional claims patterns to improve operational efficiency and healthcare accessibility.
5. Monitor High-Cost Members: Continuously monitor members contributing disproportionately to healthcare expenditure to enable early intervention and effective cost management.

# Business Value
This dashboard/report enables healthcare executives to:
* Identify key drivers of healthcare expenditure.
* Improve strategic resource allocation.
* Strengthen risk management practices.
* Support evidence-based healthcare planning.
* Enhance preventive healthcare initiatives.
* Improve financial sustainability.

# Limitations
The source dataset is **cross-sectional** and does not contain historical claim dates. Consequently, the analysis focuses on risk segmentation and healthcare cost drivers rather than longitudinal trend analysis such as month-over-month or year-over-year performance.

# Future Enhancements
Potential areas of improvement:
* Integration of historical claims data for time-series analysis.
* Incorporation of diagnosis and procedure information.
* Analysis of claims frequency and healthcare utilization.
* Provider and hospital performance analytics.

# Skills Demonstrated
* Data Cleaning
* Data Modeling
* DAX Measure Development
* Risk Segmentation
* Healthcare Analytics
* Executive Dashboard Design
* KPI Development
* Data Storytelling
* Business Intelligence
* Interactive Dashboard Development

# Conclusion
This project demonstrates how business intelligence can transform healthcare claims data into actionable insights. By identifying cost drivers, segmenting risk, and highlighting opportunities for targeted interventions, the dashboard/report provides decision-makers with the information needed to optimize healthcare spending, improve member outcomes, and support sustainable health insurance operations.
