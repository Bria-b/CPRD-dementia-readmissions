# CPRD-variable-development
# Determinants of hospital readmissions in dementia 
This repository contains Python code designed to process and analyse Clinical Practice Research Datalink (CPRD) data related to dementia patients. 

# Overview
This code processes CPRD GOLD data to:
- Process clinical, referral, and linked data including Hospital Episode Statistics (HES) and Index of Multiple Deprivation (IMD) for dementia patients
- Format and standardize date fields
- Identify dementia diagnoses using predefined code lists
- Create temporal markers around diagnosis dates
- Merge multiple data sources for comprehensive patient analysis

Required Python libraries:
pandas
numpy
glob

# Code Structure
The code includes functions for:
- Date formatting across different CPRD file types
- Data sorting and sequencing
- Long to wide format conversions
- Merging multiple CPRD data sources

Code lists were developed using published code lists and the CPRD GOLD Code Browser Version 3.0.0 (attached in this repository)

# Data Processing Steps
- Reads and processes various CPRD file types:
Clinical data
Referral data
Additional data files
Therapy data
Patient demographic data
Practice data

- Linked data (HES, IMD)
- Creates temporal markers around diagnosis dates
- Applies inclusion/exclusion criteria based on registration dates
- Processes comorbidity and medication data

  





