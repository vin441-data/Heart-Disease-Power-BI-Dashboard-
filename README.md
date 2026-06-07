# ❤️ Heart Disease Dashboard | Power BI

## 📊 Project summary

The Heart Disease Dashboard is an interactive healthcare analytics solution developed using Microsoft Power BI. This dashboard provides comprehensive insights into patient survival rates, mortality trends, age-group distribution, diabetes prevalence, and serum sodium levels.

The dashboard helps healthcare professionals, researchers, and hospital administrators identify high-risk patient groups, monitor key health indicators, and support data-driven clinical decision-making.

---

## 🎯 Project Objectives

- Analyze patient survival and mortality rates.
- Monitor heart disease trends across age groups.
- Evaluate the impact of diabetes on patient survival.
- Analyze serum sodium levels among heart disease patients.
- Identify vulnerable and high-risk age categories.
- Support evidence-based healthcare decision-making.

---

# 📌 Key Performance Indicators (KPIs)

| KPI | Value | Description |
|------|--------|-------------|
| Alive Percentage | 67.89% | Percentage of surviving patients |
| Average Age | 58.76 Years | Average patient age |
| Total Alive | 203 | Number of surviving patients |
| Total Death | 96 | Number of deceased patients |

---

# 📂 Heart Disease Dataset Overview

The dataset consists of **299 patient records** and **14 columns**, making it suitable for healthcare reporting, predictive analytics, and business intelligence projects.

---

# 📊 Dataset Summary

| Attribute | Description |
|------------|-------------|
| Dataset Name | Heart Disease Dataset |
| Total Records | 299 |
| Total Columns | 14 |
| Domain | Healthcare |
| Analysis Type | Survival & Mortality Analysis |
| Tool Used | Power BI |
| Data Type | Clinical Patient Records |

---

# 📋 Dataset Columns Explanation

| Column Name | Description |
|-------------|-------------|
| count | Unique patient record ID |
| age | Age of patient (years) |
| Hypertensions | Indicates whether patient has hypertension (0 = No, 1 = Yes) |
| muscle_damage_scale | Creatine Phosphokinase (CPK) level indicating muscle damage |
| diabetes | Indicates diabetic condition (0 = No, 1 = Yes) |
| ejection_fraction | Percentage of blood leaving heart during each contraction |
| high_blood_pressure | Indicates high blood pressure condition |
| platelets | Platelet count in blood |
| kidney_marker | Serum creatinine level indicating kidney function |
| serum_sodium | Sodium level in blood |
| sex | Gender (0 = Female, 1 = Male) |
| cancer | Anaemia condition indicator (0 = No, 1 = Yes) |
| time | Follow-up period in days |
| DEATH_EVENT | Survival status (0 = Alive, 1 = Deceased) |

---

# 🗂 Sample Dataset Structure

| ID | Age | Diabetes | High BP | Serum Sodium | Gender | Follow-up Days | Death Event |
|----|-----|----------|----------|-------------|--------|---------------|-------------|
| 1 | 75 | No | Yes | 130 | Male | 4 | Yes |
| 2 | 55 | No | No | 136 | Male | 6 | Yes |
| 3 | 65 | No | No | 129 | Male | 7 | Yes |
| 4 | 50 | No | No | 137 | Male | 7 | Yes |
| 5 | 65 | Yes | No | 116 | Female | 8 | Yes |

---

# 🩺 Medical Features Explanation

## 👴 Age
Represents patient age in years.

### Importance
- Older patients generally have higher cardiovascular risk.
- Used to identify vulnerable age groups.

---

## 💉 Hypertension

| Value | Meaning |
|---------|----------|
| 0 | No Hypertension |
| 1 | Hypertension Present |

### Importance
High blood pressure is a major risk factor for heart disease.

---

## 💊 Diabetes

| Value | Meaning |
|---------|----------|
| 0 | Non-Diabetic |
| 1 | Diabetic |

### Importance
Diabetes increases the risk of heart failure and cardiovascular complications.

---

## ❤️ Ejection Fraction

Measures how efficiently the heart pumps blood.

### Categories

| Range | Interpretation |
|----------|---------------|
| > 50% | Normal |
| 40–50% | Mild Dysfunction |
| < 40% | Severe Dysfunction |

### Importance
One of the most critical indicators of heart health.

---

## 🩸 Platelets

Platelets help blood clot properly.

### Importance
Abnormal platelet counts may indicate underlying health conditions.

---

## 🧪 Kidney Marker (Serum Creatinine)

Measures kidney function.

### Importance
Higher creatinine levels often indicate poor kidney function and increased mortality risk.

---

## 🧂 Serum Sodium

Measures sodium concentration in blood.

### Importance
Low sodium levels are associated with worse outcomes in heart failure patients.

---

## 🚻 Gender

| Value | Gender |
|---------|---------|
| 0 | Female |
| 1 | Male |

### Importance
Helps compare disease patterns between male and female patients.

---

## ⏳ Follow-Up Time

Represents the number of days a patient was monitored.

### Importance
Used for survival analysis and outcome tracking.

---

## ⚠️ Death Event (Target Variable)

| Value | Status |
|---------|---------|
| 0 | Alive |
| 1 | Deceased |

### Importance
Main variable used to analyze patient survival and mortality.

---

# 🎯 What Can Be Analyzed?

## 📈 Survival Analysis
- Alive vs Deceased Patients
- Survival Rate
- Mortality Rate
- Follow-Up Duration

## 👴 Age Analysis
- Age Distribution
- Age Group Survival
- Elderly Patient Risk Assessment

## 💉 Health Condition Analysis
- Hypertension Impact
- Diabetes Impact
- Anaemia Analysis

## ❤️ Heart Function Analysis
- Ejection Fraction Trends
- Heart Failure Severity
- Cardiac Function Monitoring

## 🩺 Clinical Metrics Analysis
- Serum Sodium Levels
- Kidney Function Analysis
- Platelet Count Evaluation

## 🚻 Demographic Analysis
- Male vs Female Comparison
- Gender-Based Mortality Analysis

---

# 📊 Dataset Insights

| Insight | Finding |
|----------|---------|
| Total Patients | 299 |
| Total Alive | 203 |
| Total Deaths | 96 |
| Survival Rate | 67.89% |
| Mortality Rate | 32.11% |
| Average Age | 58.76 Years |
| High-Risk Group | 71+ Age Group |
| Common Risk Factors | Diabetes & Hypertension |

---

# 🏥 Healthcare Significance

This dataset helps healthcare professionals:

✅ Monitor patient survival outcomes.

✅ Identify high-risk age groups.

✅ Analyze the impact of diabetes and hypertension.

✅ Study clinical indicators affecting mortality.

✅ Support evidence-based treatment decisions.

✅ Improve patient care strategies.

---

### Key Findings

✅ Nearly 68% of patients survived.

✅ Around 32% mortality rate was observed.

✅ Average patient age is approximately 59 years.

---

# 📸 Dashboard Dataset overview

<img width="1917" height="1012" alt="Image" src="https://github.com/user-attachments/assets/e5fd60e7-fb1b-4713-a5c8-f4e60adb52d4" />

---

<img width="1918" height="1017" alt="Image" src="https://github.com/user-attachments/assets/bcff6e26-ad85-4c6a-b237-9d4b626a8a83" />

---

# 📈 Dashboard Visualizations

## 1️⃣ Total Alive by Age Group

### Visualization Type
Clustered Column Chart

### Purpose
Displays the number of surviving patients across different age categories.

### Insights

| Age Group | Total Alive |
|------------|------------|
| 51–60 | 63 |
| 61–70 | 63 |
| 40–50 | 55 |
| 71+ | 21 |
| Blank | 1 |

### Key Insight

- Highest survival occurs in the 51–70 age group.
- Survival decreases significantly after age 70.

### Business Value

- Supports age-based healthcare planning.
- Helps identify vulnerable patient groups.

---

## 2️⃣ Average Serum Sodium by Age Group

### Visualization Type
Line and Column Combo Chart

### Purpose
Analyzes average serum sodium levels among patients across age groups.

### Insights

- Average serum sodium remains between 136–137 mEq/L.
- Patients aged 71+ show slightly elevated sodium levels.
- Overall variation remains minimal.

### Healthcare Importance

- Detects electrolyte imbalance.
- Supports cardiovascular risk assessment.

---

## 3️⃣ Total Alive by Age Group Trend

### Visualization Type
Area Chart

### Purpose
Visualizes survival trends across age categories.

### Key Findings

| Age Group | Alive Count |
|------------|------------|
| 51–60 | 63 |
| 61–70 | 63 |
| 40–50 | 55 |
| 71+ | 21 |

### Insights

- Strong survival rates among middle-aged patients.
- Significant decline among elderly patients.

### Value

- Supports targeted healthcare interventions.

---

## 4️⃣ Total Alive vs Diabetes Analysis

### Visualization Type
Stacked Area Chart

### Purpose
Compares survival counts with diabetes prevalence.

### Findings

| Age Group | Alive | Diabetes Cases |
|------------|--------|---------------|
| 51–60 | 63 | 40 |
| 61–70 | 63 | 37 |
| 40–50 | 55 | 33 |
| 71+ | 21 | 21 |

### Healthcare Value

- Supports diabetic patient monitoring.
- Helps identify high-risk populations.

---

## 5️⃣ Gender Analysis

### Interactive Filters

- Male
- Female

### Purpose

Allows users to analyze survival and mortality patterns separately for male and female patients.

### Insights

- Compare gender-specific risk factors.
- Study demographic trends.
- Evaluate healthcare outcomes by gender.

---

## ❤️ Dashboard Design Elements

### Heart Illustration

The 3D heart visualization enhances the dashboard's healthcare theme and improves overall user engagement.

### Benefits

- Professional appearance
- Better storytelling
- Improved dashboard usability

---

# 📊 Key Insights

### Survival Analysis

✅ Total Alive Patients: 203

✅ Total Death Cases: 96

✅ Survival Rate: 67.89%

---

### Age Analysis

✅ Most patients belong to the 51–70 age category.

✅ Survival decreases significantly after age 70.

---

### Health Indicators

✅ Average Age: 58.76 Years

✅ Serum Sodium levels remain relatively stable across groups.

---

# 📈 Healthcare Impact

This dashboard helps:

- Hospitals monitor patient outcomes.
- Doctors identify high-risk patients.
- Researchers analyze disease patterns.
- Healthcare organizations improve treatment planning.
- Support evidence-based medical decisions.

---

# 🛠 Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning
- Data Visualization
- Healthcare Analytics

---

# 📚 Skills Demonstrated

- Healthcare Data Analysis
- Power BI Dashboard Development
- KPI Design
- DAX Measures
- Data Modeling
- Interactive Reporting
- Data Storytelling
- Medical Analytics
- Data Visualization

---

# 📸 Dashboard Summary

<img width="1918" height="1018" alt="Image" src="https://github.com/user-attachments/assets/df10c2d6-3a22-49d4-b3c1-8d84d89c2b22" />

The Heart Disease Dashboard delivers a comprehensive view of patient survival, mortality rates, diabetes prevalence, serum sodium levels, and age-group distribution. Through interactive visualizations and KPIs, the dashboard empowers healthcare professionals to gain meaningful insights and improve patient care outcomes.

---

## 🚀 Future Enhancements

- Predictive Survival Analysis
- Heart Disease Risk Scoring
- Machine Learning Integration
- Patient Segmentation
- Real-Time Healthcare Monitoring
- Clinical Performance Tracking

---

## ⭐ Project Outcome

This project demonstrates how Power BI can transform healthcare data into actionable insights by enabling efficient monitoring of patient outcomes, risk factors, and treatment effectiveness.

---
