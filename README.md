# Telecom Customer Churn Analysis

![](daba-finance-invest-africa-1744684087728-orange.png)


## Project Overview
The objective of this project was to transform raw telecom customer data into meaningful business insights using  interactive dashboards in Power BI.  

The project focuses on identifying patterns that influence **customer churn**, including service subscriptions, customer complaints, usage behavior, and customer tenure.  

Two dashboards were created to explore:
- **Churn drivers**
- **Customer behavior patterns**

The final dashboards present key metrics and trends to support **data-driven decision making for telecom customer retention strategies.**

**Disclaimer:**  
All datasets and reports do not represent any company, institution, or country. They are **dummy datasets used solely to demonstrate Power BI data analysis and visualization capabilities.**

---

# Data Sources
This project uses a telecom churn dataset stored as a CSV file containing customer-level information about telecom usage and services.

The dataset includes the following key variables:

### Customer Information
- State
- Area Code
- Account Length

### Service Plans
- International Plan
- Voice Mail Plan

### Usage Metrics
- Total Day Minutes  
- Total Evening Minutes  
- Total Night Minutes  
- Total International Minutes  

### Call Metrics
- Total Day Calls  
- Total Evening Calls  
- Total Night Calls  
- Total International Calls  

### Charges
- Total Day Charge  
- Total Evening Charge  
- Total Night Charge  
- Total International Charge  

### Customer Interaction
- Customer Service Calls

### Target Variable
- Churn (True/False)

---

# Problem Statement
The analysis aims to answer the following business questions:

- Do international plan users churn more?
- Do customer service complaints increase churn?
- Does voicemail plan affect churn?
- Does voicemail plan affect churn?
- Do heavy users churn more?
- Do heavy users churn more?
- Do frequent callers churn more?
- How often do customers contact support?
- How common are telecom service features?
- What are the call patterns during the day?

---

# Key Skills Demonstrated

### Power Query
- Data cleaning and transformation  
- Feature creation and column engineering  

### Data Modeling
- Structuring datasets for analysis  
- Creating calculated columns  

### DAX
- Calculated columns and measures including:
  - Churn Rate
  - Average Revenue Per User (ARPU)
  - Total Minutes
  - Total Charges
  - Call Frequency Bins
  - Account Length Bins

### Power BI
- Interactive dashboards  
- Business-focused data visualization  
- Slicers and filters for user interaction  

---

Several calculated fields were created to enhance the analysis:

### Calculated Columns

**Total Minutes**  
Sum of all call minutes:
