# Hospital Readmission EDA

## Overview
This project performs Exploratory Data Analysis (EDA) on a hospital readmission dataset to understand patterns related to **30-day patient readmission**.  
The focus is on identifying which patient and hospital factors are associated with a higher risk of returning to the hospital within 30 days.

---

## Dataset
**Source:** [Diabetes 130-US Hospitals Dataset (Kaggle)](https://www.kaggle.com/datasets/brandao/diabetes/data?select=diabetic_data.csv)  

**Target Variable**
- `readmit_30`, where,
  - `1` → Readmitted within 30 days
  - `0` → Not readmitted within 30 days

---

## What This Analysis Explores
- Overall rate of 30-day readmission
- Impact of prior hospital visits on readmission risk
- Diagnosis-level readmission rates
- Length of hospital stay vs readmission

---

## Methods Used
- Data cleaning and inspection
- Feature changes to binary readmission changes
- Missing value analysis
- Categorical vs numerical feature separation
- Visualizations:
  - Count plots
  - Box plots
  - Readmission rate bar charts
  - Correlation heatmap

---

## Key Findings were:
- **30-day readmission is uncommon (~11%)**, making this an imbalanced outcome.
- **Patients with multiple prior inpatient visits have much higher readmission risk.**
- **Some diagnoses show significantly higher readmission rates than others.**
- **Length of stay alone does not strongly separate readmitted vs non-readmitted patients.**
- Readmission appears to be a **multifactor problem**, not driven by a single variable.


