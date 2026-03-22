# Executive Insights Dashboard - Telecom Churn Dataset

![](daba-finance-invest-africa-1744684087728-orange.png)

---

## Project Overview

The objective of this project was to analyze telecom customer data and transform it into **actionable business insights** using Power BI.

The project leverages the **Orange Telecom Churn Dataset**, which contains customer activity data along with a churn label indicating whether a customer canceled their subscription.


This project focuses on building **executive dashboards** that:
- Identify **key churn drivers**
- Highlight **high-risk customer segments**
- Support **data-driven retention strategies**

---

## Dataset Description

Each row represents a customer, and each column represents customer attributes.

### Features

- State  
- Account length  
- Area code  
- International plan  
- Voice mail plan  
- Number of voicemail messages  
- Total day minutes  
- Total day calls  
- Total day charge  
- Total evening minutes  
- Total evening calls  
- Total evening charge  
- Total night minutes  
- Total night calls  
- Total night charge  
- Total international minutes  
- Total international calls  
- Total international charge  
- Customer service calls  
- Churn (Target Variable)  

The dataset contains **667 customers and 20 features**.

---
 

## Research Questions

### Customer Service Performance

- What is the relationship between **customer service calls and churn probability**?
- Is there a **tipping point (e.g., 3+ calls)** that increases churn risk?
- Do churned customers have **higher call frequency** than retained customers?
- Are there **geographic regions with higher service issues**?

---

### Plan & Usage Drivers

- Do customers with an **International Plan churn more**?
- Is there a difference in **charges between churned and retained customers**?
- Does a **Voice Mail Plan improve retention**?
- Does **customer tenure influence churn risk**?

---

## Tailored Business Goals

- Identify a **critical call threshold** to trigger retention actions  
- Evaluate **regional service quality issues**  
- Review **International Plan pricing and value**  
- Design **loyalty programs based on tenure**  
- Optimize support to resolve issues in **< 3 calls**  
- Promote **Voice Mail Plan adoption**  
- Conduct **price sensitivity analysis**  
- Segment customers into **risk tiers (High, Medium, Low)**  

---

## Data Cleaning & Preparation
---

### Data Transformation (Power Query)

- Converted categorical fields (Yes/No → True/False)  
- Created:

#### Total Charge Column
Sum of all charge components:
- Day + Evening + Night + International  

#### Call Frequency Bins
- Low (0–2calls)  
- Medium (3–5 calls)  
- High (6-9 calls)  

---

### Data Modeling

- Created a **Measures Table (_Measures)**  
- Organized all DAX calculations in one place  

---

### Key Measures

####  DAX
- Measures created include:
  - Churn Rate  
  - ARPU (Average Revenue Per User)  
  - Customer Service Call Average  
  - Churn MoM % Change  
  - Risk Tier Segmentation
 
---

 ## Analysis

### Analysis Objectives

### Objective 1: Customer Service Performance
Understand how **customer service interactions influence churn**, including identifying dissatisfaction patterns.

### Objective 2: Plan & Usage Drivers
Analyze how **service plans, billing, and usage behavior** contribute to churn.


Visualizations such as bar charts, column charts, line charts, and scatter plots were used to identify trends and relationships within the data.

#### Visualization and Key Questions Answered

Two dashboards were designed in Power BI to present insights from different analytical perspectives.

Dashboard 1: Telecom Customer Churn Analysis: Customer Service Performance


### Key Visuals

#### Cards

Total Customers: 2,666
Total Churned Customers: 388
Churn Rate: 14.55%
Average Revenue Per User (ARPU): $59
WHAT IS THE OVERALL CUSTOMER CHURN RATE?

Out of 2,666 total customers, 388 customers churned, resulting in a 14.55% churn rate.

This indicates that roughly 1 in every 7 customers leaves the telecom service, highlighting the need for targeted retention strategies.

##### What is the relationship between the frequency of customer service calls and the probability of a customer churning?

Customers with high call frequency recorded a churn rate of 64.29%.
Mid-frequency callers had a churn rate of 24.53%, while low-frequency callers had 11.39%.

##### Is there a specific number of service calls (e.g., 3 or more) that serves as a "tipping point" for customer dissatisfaction?
The line chart shows a clear tipping point after 3–4 service calls, where churn begins to increase sharply.
This suggests that frequent customer service interactions are a strong predictor of churn and indicate unresolved customer issues.

##### Do churned customers exhibit a higher average call frequency compared to loyal customers?
Churned customers consistently show higher average customer service calls compared to retained customers.
This indicates that customers who churn tend to have repeated service issues before leaving.

##### Are there specific states or area codes where customer service call rates are significantly higher, indicating regional service issues?
The map highlights states with higher customer service call volumes, indicating potential regional service challenges.
This suggests that some regions may require targeted service improvements or infrastructure upgrades.

Dashboard 2: Telecom Customer Behaviour Analysis

This dashboard focuses on understanding customer usage behavior and service adoption patterns.

DO CUSTOMERS WITH INTERNATIONAL PLANS CHURN MORE?
Customers with an International Plan recorded significantly higher churn rates compared to those without.

This suggests that the international plan may be perceived as expensive or low value, driving customer attrition.

DOES HAVING A VOICE MAIL PLAN REDUCE CHURN?
Customers with a Voice Mail Plan show lower churn rates compared to those without.

This suggests that value-added services improve customer retention and loyalty.

DO LOW-VALUE CUSTOMERS CHURN MORE?
The revenue comparison shows that churned customers contribute significantly less total revenue compared to active customers.

This indicates that low-value customers are more likely to churn, making them a key segment for retention strategies.

DOES TENURE AFFECT CHURN?
Mid-tenure customers show the highest churn risk, compared to new and long-tenure customers.

This suggests that customers are most vulnerable during the mid-stage of their lifecycle, making it a critical point for engagement and retention efforts.

Key Insights & Findings
The dataset contains 2,666 customers, with 388 churned, resulting in a 14.55% churn rate.
Customers with high customer service calls are significantly more likely to churn.
A clear churn tipping point exists after 3–4 service calls.
Customers with an International Plan show higher churn rates.
Customers with a Voice Mail Plan show lower churn rates, indicating better retention.
Mid-tenure customers have the highest churn risk.
Regional differences exist in customer service demand, indicating uneven service quality.
Low-value customers contribute more to churn, highlighting a key risk segment.
Recommendations
Improve Customer Support Experience

Customers making multiple service calls are more likely to churn. Improving issue resolution speed and support quality is critical.

Identify Critical Call Threshold

Trigger retention actions once a customer exceeds 3–4 service calls.

Review International Plan Strategy

Reassess pricing and value proposition of the international plan.

Promote Value-Added Services

Encourage adoption of Voice Mail Plans to improve customer retention.

Focus on Mid-Tenure Customers

Introduce loyalty programs and engagement strategies during the mid-customer lifecycle stage.

Target High-Risk Regions

Address regional service gaps identified in high-call areas.

Project Access

Click here to access the project files 
