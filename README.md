# **🏥 Patient_Diagnostic_Dashboard**

# **📊 Patient Diagnostic & Clinical Analytics Dashboard**

# **🔎 Project Overview**

This project analyzes patient diagnostic data to provide clinical insights, risk identification, and healthcare trends using Power BI.

The dashboard integrates patient demographics, diagnostic test results, symptoms, and visit behavior to help healthcare professionals monitor patient conditions, detect risks early, and support data-driven decisions.

# **🎯 Business Objective**

The goal of this analysis is to:

Identify high-risk patients
Monitor clinical indicators (WBC, RBC, Platelets)
Analyze patient visit trends over time
Evaluate infection and medical condition distribution
Detect abnormal diagnostic results
Support proactive healthcare decision-making

🏗️ Data Model

The report is built using a star schema model.

Fact Table
Fact_Patient (Patient_ID, Visit_ID, Risk_Level, Temperature, Weight, Symptoms)
Supporting Tables
Blood_Test_Results (WBC, RBC, Platelets, CRP, Hemoglobin, etc.)
Fever_Type_Profile (Fever categories and clinical mapping)
Medication (Treatment details)
Date_Table (Time intelligence)
Key Modeling Practices
One-to-many relationships
Single-direction filtering
Calculated columns (Medical Condition, Age Group, Severity)
Optimized DAX measures
Clean and scalable model design
📌 Key KPIs
Total Patients
Total Visits
High Risk %
Average Temperature
Average Weight
Average WBC
Average RBC
Average Platelets
Total Blood Tests
# **📄 Dashboard Structure**
### **Page 1 – Overview**

High-level patient summary:

Patient Visit Trend Over Time
Patient Risk Distribution
Patient Distribution by Gender
Patient Distribution by Age Group
### **Page 2 – Clinical Diagnostics**

Detailed clinical insights:

WBC Diagnostic Trend
Patient Distribution by WBC Level
Patient Distribution by Infection Type
Risk Distribution Across Fever Types (Heatmap)
Blood test KPI indicators
### **Page 3 – Patient Details**

Patient-level drill-down:

Complete patient diagnostic records
Risk-level highlighting (Low / Medium / High)
Symptom indicators (Rash, etc.)
Conditional formatting for abnormal values
Filtering for detailed investigation
## **📊 Key Insights**
A significant portion of patients fall under Medium to High Risk categories
WBC levels fluctuate across months, indicating possible infection trends
Viral and vector-borne infections dominate the dataset
Certain fever types show higher concentration of high-risk patients
Diagnostic indicators help identify early warning signals for critical cases
## **🛠️ Tools & Technologies**
Power BI Desktop
DAX (Data Analysis Expressions)
Power Query
Star Schema Data Modeling
## **🚀 How to Use**
Download the .pbix file from this repository
Open in Power BI Desktop
Use slicers to filter by:
Year
Risk Level
Fever Type
Medical Condition
Navigate across pages:
Overview → Clinical Diagnostics → Details
## **⚠ Disclaimer**

This is generated using AI and demographic data; the results may not be fully accurate.

## **🖼️ Dashboard Preview**
Page 1 – Overview

Page 2 – Clinical Diagnostics

Page 3 – Patient Details

## **👤 Author**

# **Aravind Teja Bastipadu**
Designed and built using Power BI 2026 MAR
