# Massachusetts-General-Hospital-Analysis: Optimizing Patient Admissions and Resource Allocation at Massachusetts General Hospital
## Table Of Content
  - [Description](#description)
  - [Business Introduction](#business-introduction)
  - [Business Problem](#business-problem)
  - [Aim Of Analysis](#aim-of-analysis)
  - [Processes](#processes)
  - [Key Insights](#key-insights)
  - [Recommendations](#recommendations)

### Description 
This project showcases my expertise in designing an end-to-end data analytics solution using Power BI for the healthcare industry. It involves data integration, visualization, and actionable insights to enhance hospital performance monitoring.

![Screenshot 2025-03-21 022603](https://github.com/user-attachments/assets/6a7bd831-1d83-4cc4-9c2a-736adac0dbc4)

### Business Introduction
Massachusetts General Hospital (MGH) is one of the oldest and most renowned hospitals in the United States. Founded in 1811 in Boston, Massachusetts, MGH is a Harvard Medical School teaching hospital and a leader in medical research, patient care, and innovation. It is consistently ranked among the top hospitals in the country, known for its excellence in specialized treatments, advanced healthcare technology, and groundbreaking medical discoveries. MGH serves a diverse patient population and plays a vital role in improving healthcare outcomes both locally and globally.

### Business Problem
Massachusetts General Hospital (MGH) is experiencing challenges in managing patient admissions, readmissions, and healthcare resource allocation. Without clear data-driven insights, it becomes difficult to identify patterns, optimize costs, and enhance patient care.

Some key concerns include:

- High Readmission Rates: Frequent patient returns may indicate gaps in post-discharge care, treatment effectiveness, or hospital capacity issues.
- Uneven Patient Distribution: Certain locations might contribute more to patient admissions, potentially leading to overburdened hospital facilities in specific areas.
- Demographic Trends in Admissions: Understanding variations in admissions based on age, gender, and race can help in designing targeted healthcare strategies.
- Cost Management: Rising hospital visit costs may require budget optimization strategies to balance expenses while maintaining high-quality care.
- Length of Stay Impact: It is crucial to assess whether hospital stay durations influence readmissions, resource utilization, and patient outcomes.

### Aim Of Analysis
The aim of this project is to analyze key hospital performance metrics, patient demographics, procedure costs, and readmission rates at Massachusetts General Hospital. By leveraging data-driven insights, this analysis seeks to identify potential inefficiencies, patterns in patient care, and cost drivers. Additionally, it aims to explore factors contributing to patient readmissions and overall resource utilization. This will help stakeholders make informed decisions to improve hospital efficiency, enhance patient outcomes, and optimize financial performance.

### Processes 
#### 1  Data Cleaning & Preparation
Tool: Power Query (Power BI) 
-	The dataset containing hospital records, patient demographics, procedure details, and payer information is collected and imported for analysis.
-	Handling missing values, correcting inconsistencies, formatting columns (e.g., dates, numeric values), and removing duplicate records.
#### 2  Data Transformation & Modeling
Tool: Power BI (Data Model, DAX)
- Creating relationships between tables (e.g., linking patient admissions to procedures and encounter).
-	Adding calculated columns and measures (e.g., Total Procedure Cost, Readmission Rate).
#### 3 Exploratory Data Analysis (EDA)
Tool: Power BI
-	Identifying key trends, patterns, and outliers using visualizations like bar charts, line graphs, and pie charts.
-	Defining metrics such as Total Procedure Cost, Average Cost per Visit, and Readmission Rate.
-	Creating dynamic KPI cards for easy monitoring.
#### 4 Dashboard Design & Visualization
Tool: Power BI Visualization Features 
-	Developing interactive dashboards showcasing hospital costs, patient admissions, readmission rates, and payer coverage.
-	Using slicers and filters to enable dynamic analysis.

### Key Insights
1. High Total Procedure and Encounter Costs
-	The Total Procedure Cost is $105.5M, while the Total Encounter Cost is $101.5M, indicating significant healthcare spending.
-	The Average Procedure Cost is $2.2K, and the Average Encounter Cost is $3.6K, suggesting higher costs per patient visit.
2. Top Cost-Driving Procedures
-	Atrial Fibrillation ($39M), Normal Procedures ($30M), and Normal Pregnancy ($20M) are the top reasons for high procedure costs.
-	Renal Dialysis ($2.75M) has a notable cost impact despite having fewer procedures compared to other assessments.
3. Payer Coverage Distribution
-	Medicare (19.2M) and Medicaid (8.4M) cover the majority of the procedures, indicating a heavy reliance on government-sponsored health insurance.
-	Private insurers such as Blue Cross Blue Shield and United Healthcare have significantly lower coverage.
4. Trends in Procedures and Encounters Over Time
-	A peak in procedures and encounters occurred in 2014 (6.3K procedures, 3.9K encounters), followed by a decline.
-	A sharp drop is observed in 2022, which could be due to external factors such as policy changes or COVID-19-related hospital capacity adjustments.
5. Patient Demographics and Readmissions
-	Total Patient Admissions: 974
-	Total Readmissions: 854, indicating a high readmission rate.
-	Older patients (1921-1940 age group) have the highest admissions (353 cases), suggesting they may require more intensive care and monitoring.
-	Suffolk County has the highest patient admissions (644), followed by Norfolk County (155).
6. Encounter Classifications
-	Ambulatory (12.5K) and Outpatient (6.3K) encounters dominate, while inpatient encounters (1.1K) are significantly lower.
-	Chronic diseases such as heart failure, hyperlipidemia, and viral infections are among the top encounter reasons.

### Recommendations
1. Cost Optimization Strategies
-	Focus on cost reduction in high-cost procedures like Atrial Fibrillation and Renal Dialysis through alternative treatments or early intervention programs.
-	Introduce preventative health programs for chronic conditions to reduce long-term treatment costs.
2. Addressing High Readmission Rates
-	Implement post-discharge follow-up programs for high-risk patients to reduce readmissions.
-	Develop remote monitoring and home healthcare initiatives to support elderly patients and reduce the need for rehospitalization.
3. Insurance & Billing Strategy
-	Work with private insurers to increase coverage and reduce the financial burden on Medicare and Medicaid.
-	Introduce value-based care models to align treatment costs with patient outcomes.
4. Resource Allocation & Planning
-	Allocate more resources to ambulatory and outpatient services to manage the high patient volume efficiently.
-	Investigate the sharp drop in procedures and encounters in 2022 and develop strategies to stabilize hospital utilization.
5. Enhancing Preventative Care for Chronic Diseases
-	Increase early screening programs for conditions such as heart failure and hyperlipidemia to reduce severe cases.
-	Strengthen patient education on lifestyle modifications to prevent chronic disease progression.
#### By implementing these recommendations, Massachusetts General Hospital can improve patient care, reduce costs, and enhance operational efficiency.

