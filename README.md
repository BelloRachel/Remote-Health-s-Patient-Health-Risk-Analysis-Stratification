# Remote Health - Patient Health Risk Analysis Stratification
Health risk stratification analysis using patient vitals and demographics to classify patients into Low, Medium, and High risk categories. Built with Excel, this project helps identify at-risk patients for proactive care and improved health outcomes.

## Introduction

RemoteHealth is a digital healthcare platform that provides remote consultations, patient monitoring, and coordinated care services. As digital health adoption grows, proactively identifying higher-risk patients is critical to:
- Prevent emergencies
- Improve patient outcomes
- Optimize clinical resources
This analysis uses patient data and vital signs to stratify risk and support proactive patient care.

## Objectives

- Identify patients with abnormal vital signs
- Classify patients into Low, Medium, and High Risk categories
- Analyze health risk patterns across age groups
- Examine the relationship between chronic conditions and health risk
- Provide actionable, data-driven recommendations

  ## Dataset Description

Two datasets were integrated:
- **Patients Dataset:** Demographics (age, gender, chronic conditions)
- **Vitals Dataset:** Blood pressure, heart rate, glucose levels
Merged using Patient ID for a comprehensive view.
<img width="1610" height="190" alt="image" src="https://github.com/user-attachments/assets/0a4b3032-a810-4e02-aac0-6b66878eb8c1" />

## Methodology & Risk Definition

### Vital Sign Thresholds
- Blood Pressure - < 140/90, Systolic ≥ 140 OR Diastolic ≥ 90 
- Heart Rate - 60–100 bpm, < 60 bpm OR > 100 bpm 
- Glucose - < 140 mg/dL, ≥ 140 mg/dL 
<img width="704" height="176" alt="image" src="https://github.com/user-attachments/assets/ea9fe269-faa0-4c95-baff-47e13879a813" />

### Risk Classification
- 0 - Low Risk
- 1 - Medium Risk 
- 2 -|High Risk

  ##  Key Findings
  <img width="503" height="556" alt="image" src="https://github.com/user-attachments/assets/a8f3c696-fdf8-4bf9-8ed6-de23144e05bc" />

### 1. Risk Category Distribution
- Most patients fall into **Medium Risk** (at least one abnormal vital)
- A smaller group is **High Risk** – requiring urgent or continuous monitoring

### 2. Health Risk by Age Group
- 30–39 - Low Risk 
- 40–59 - Medium Risk
- 60+ - Highestrisk
Health risk increases with age.

### 3. Chronic Conditions & Risk
- Diabetes -  Medium/High Risk (elevated glucose)
- Hypertension - Strongly associated with abnormal BP
- No chronic conditions - Mostly Low Risk

##  Dashboard Preview

<img width="1123" height="687" alt="image" src="https://github.com/user-attachments/assets/98eaa948-e836-4127-962e-0c43e316671d" />


The dashboard includes:
- Patient distribution by risk category
- Risk levels by age group
- Risk distribution across chronic conditions
- Key indicators (total patients, high-risk count)

##  Business Recommendations
Based on the analysis, the following recommendations are proposed:
- Proactive Monitoring:
High-risk patients, especially those aged 60 and above, should be enrolled in continuous remote monitoring programs to reduce emergency events.

- Targeted Diabetes Management:
Patients with diabetes should receive enhanced glucose monitoring, regular virtual consultations, and lifestyle guidance to manage risk effectively.

- Risk-Based Care Prioritization:
 Risk classification should be integrated into clinical workflows to prioritize appointments, follow-ups, and preventive care for higher-risk patients.

##Conclusion
This project demonstrates how patient vitals and medical history data can be transformed into meaningful insights through systematic risk stratification. By applying clinically accepted thresholds and transparent analytical methods, RemoteHealth can proactively identify at-risk patients and improve healthcare outcomes.
The findings support the use of data-driven decision-making as a foundation for efficient resource allocation, preventive care, and improved patient management.

##  Links
https://docs.google.com/document/d/1WRah5zfdE4vy5bz3XOFIBx_0YjWxtL_BYkmxKOBxSmo/edit?usp=drive_link
https://docs.google.com/document/d/1bPq6pRPR_lfgbJyqeCk5NLcJQr_04xjlN048SQoXEaA/edit?usp=drive_link
