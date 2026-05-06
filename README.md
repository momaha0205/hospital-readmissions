# Hospital Readmission Risk Analysis

## Overview
End-to-end data analysis identifying early hospital readmission risk factors 
in diabetic patients across 130 US hospitals (1999–2008). Built with Python.

## Business Question
What factors are most associated with early hospital readmission in diabetic 
patients, and how can hospitals reduce them?

## Key Findings
- 8.8% of patients were readmitted within 30 days — roughly 1 in 11
- Patients aged 80-90 had the highest early readmission rate at 10.4%
- Longer hospital stays do not prevent readmission — rates peaked at 12.0% for 8-day stays
- Readmission rates rose from 4.2% to 12.9% as medication count increased
- Hematology/Oncology had the highest specialty rate at 18.0%
- Medication changes signal patient severity, not cause of readmission

## Tools Used
- Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Dataset
- Source: Kaggle — Diabetes 130 US Hospitals (1999–2008)
- 101,766 raw records | 71,515 unique patients after cleaning

## Files
- hospital_readmissions_eda.ipynb — full analysis notebook
- diabetic_data_cleaned.csv — cleaned dataset
