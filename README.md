# **🏥 Patient_Diagnostic_Dashboard**

# **📊 Patient Diagnostic & Clinical Analytics Dashboard**

# **🔎 Project Overview**

This project analyzes patient diagnostic data to deliver clinical insights, risk identification, and decision support using Power BI.

The dashboard integrates patient demographics, symptoms, and blood test results to not only monitor patient conditions but also assist doctors in suggesting possible diseases and medications based on clinical inputs.

# **🎯 Business Objective**
The goal of this analysis is to:

Identify high-risk patients
Monitor key clinical indicators (WBC, RBC, Platelets)
Analyze patient visit trends
Evaluate infection and medical condition distribution
Detect abnormal diagnostic patterns
Build a clinical decision support system for diagnosis and treatment

🏗️ Data Model
The report is built using a star schema model.
<img width="1135" height="719" alt="image" src="https://github.com/user-attachments/assets/bfc184b7-2899-46d0-be40-d7fa7f73ed6b" />


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

High-level summary of patient data:

Patient Visit Trend Over Time
Patient Risk Distribution
Patient Distribution by Gender
Patient Distribution by Age Group
### **Page 2 – Clinical Diagnostics**

Detailed clinical insights:

WBC Diagnostic Trend
Patient Distribution by WBC Level
Patient Distribution by Infection Type
Risk Distribution Across Fever Types
Blood test KPI indicators
### **Page 3 – Diagnosis & Recommendation**

This is the core highlight of the project.

A clinical decision support system where:

Doctor selects a patient
Doctor marks symptoms
Dashboard analyzes blood report
System suggests Disease & Medication
Doctor finalizes the decision

Key Features:

🦠 Suggested Disease
💊 Recommended Medication
⚠ Patient Risk Status
🧾 Clinical Insight (AI-assisted explanation)
👨‍⚕️ Doctor Final Decision input
### **Page 4 – Patient Details** 
Detailed patient-level analysis:

Complete diagnostic records
Risk-level highlighting (Low / Medium / High)
Symptom indicators
Conditional formatting for abnormal values
Advanced filtering for investigation
## **📊 Key Insights**
A large portion of patients fall under Medium to High Risk categories
WBC trends indicate infection patterns over time
Viral and vector-borne infections are most common
Certain fever types show higher concentration of high-risk patients
Clinical indicators help identify early warning signals for severe conditions
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
Overview → Clinical Diagnostics → Diagnosis → Details
## **⚠ Disclaimer**

This is generated using AI and demographic data; the results may not be fully accurate.

## **🖼️ Dashboard Preview**
Page 1 – Overview
<img width="1371" height="772" alt="PBD_Overview" src="https://github.com/user-attachments/assets/9ea26357-f53b-456b-89fd-3ebdd6ecacea" />


Page 2 – Clinical Diagnostics
<img width="1375" height="776" alt="PBD_ClinicalDiagnostic" src="https://github.com/user-attachments/assets/61171e85-f92a-47f1-8032-1967717c96e8" />

Page 3 – Diagnosis & Recommendation
<img width="1374" height="772" alt="Screenshot 2026-03-29 172253" src="https://github.com/user-attachments/assets/1d12bb4f-1580-496f-a852-3100d5424824" />


Page 4 – Patient Details
<img width="1376" height="765" alt="PBD_Details" src="https://github.com/user-attachments/assets/3f79dbfc-df9f-4079-bec3-3223ac8f6c54" />


## **👤 Author**

# **Aravind Teja Bastipadu**
Designed and built using Power BI 2026 MAR
