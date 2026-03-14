# Air Quality Analysis Dashboard

## The Problem
Air pollution has become one of the most serious environmental and public health challenges in India. Rapid urbanization, increasing vehicle emissions, and industrial growth have significantly impacted air quality in many cities.

Although large volumes of air quality data are collected across different regions, raw datasets alone do not provide clear insights. Without proper analysis and visualization, it becomes difficult to identify pollution trends, compare cities, or understand the severity of air quality issues.

This project transforms raw air quality data into meaningful insights through data analysis and visualization.

---

## Objective
The objective of this project is to analyze air quality data across multiple cities and states in India and build an interactive dashboard that helps identify pollution trends and patterns.

The dashboard allows users to:
- Understand AQI trends over time
- Identify the most polluted cities
- Compare air quality across different states
- Explore the distribution of air quality categories
- Analyze pollution patterns using interactive filters

---

## Dataset
The dataset used in this project was collected from:

National Data & Analytics Platform (NDAP)  
NITI Aayog, Government of India  
https://ndap.niti.gov.in

Dataset includes:
- City
- State
- AQI Value
- AQI Category
- Date

---

## Tools and Technologies

| Tool | Purpose |
| --------------------- | --------------------------------------- |
| Microsoft Power BI    | Dashboard development and visualization |
| Microsoft Excel / CSV | Data storage                            |
| Power Query           | Data cleaning and transformation        |
| DAX                   | Creating calculated measures and KPIs   |

---

## Data Preparation
Before analysis, the dataset was cleaned and transformed using Power Query.

The following preprocessing steps were performed:
- Promoted headers and corrected column names
- Converted columns to appropriate data types
- Removed duplicate records
- Cleaned text values and removed extra spaces
- Filtered unnecessary rows and columns
- Created a conditional column to correctly sort AQI categories

These steps ensured the dataset was ready for analysis.

---

## Dashboard Features
The Power BI dashboard includes:

- KPI Cards showing Average AQI, Maximum AQI, and Minimum AQI
- AQI Trend Line Chart to analyze pollution changes over time
- State-wise AQI comparison using bar charts
- Top 10 most polluted cities visualization
- AQI category distribution using a donut chart
- City-wise AQI map for geographic visualization
- Interactive filters for City, State, and Date

---

## Dashboard Preview

![Dashboard](dashboard.png)

---

## Key Insights
Some key observations from the analysis include:

- Certain cities consistently show higher AQI levels.
- Air quality varies significantly across different states.
- Pollution levels fluctuate over time.
- Many observations fall into moderate or poor air quality categories.

These insights highlight the importance of monitoring air quality and taking appropriate environmental actions.

---

## Conclusion
This project demonstrates how data visualization tools can convert complex environmental data into meaningful insights.

The Air Quality Analysis Dashboard provides a clear and interactive way to understand pollution patterns and identify areas that require attention.

---

## Author
Abhinav Kumar  
Department of Electronics & Communication Engineering  
ZHCET, AMU
