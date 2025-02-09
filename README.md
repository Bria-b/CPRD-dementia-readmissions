# Determinants of hospital readmissions in dementia - CPRD data variable development and analyses
This repository contains code designed to process, analyse, and model Clinical Practice Research Datalink (CPRD) data related to patients with dementia with at least one hospital admission. The data processing was performed using Python version 3.9.7, and further statistical analyses were conducted in RStudio version 4.4.2.

# Overview
This project processes CPRD GOLD data to:
- Handle and merge clinical, referral, and linked datasets (including Hospital Episode Statistics - HES and Index of Multiple Deprivation - IMD).
- Format and standardise date fields across datasets.
- Identify dementia diagnoses using predefined code lists.
- Create temporal markers around the dementia diagnosis dates.
- Merge multiple files containing clinical information, referrals, test results, and patient/practice data for comprehensive analysis.

Further statistical analyses were conducted in RStudio to:
- Prepare data and perform descriptive and exploratory statistics.
- Conduct logistic and Cox regression analyses to evaluate risk factors and outcomes associated with hospital readmissions among older adults with dementia.


# Code Structure
Python Scripts:
- The Python script performs data extraction, cleaning, formatting, and merging of multiple datasets.
- Data processing functions include date formatting, sorting, merging, and creating indicator variables.
- Code lists were developed using published code lists and the CPRD GOLD Code Browser Version 3.0.0 (attached in this repository).

RStudio Analyses:
- Data preparation and exploratory analyses were conducted using RStudio.
- Further modelling was performed using logistic regression and Cox proportional hazards regression, to assess the relationships between predictor variables and hospital readmission outcomes.


# Data Processing Steps (Python)
Reads and processes various CPRD file types:
- Clinical data
- Referral data
- Additional data files
- Therapy data
- Patient demographic data
- Practice data

Linked data (HES, IMD)

Creates temporal markers around diagnosis dates

Applies inclusion/exclusion criteria based on registration dates

Processes comorbidity and medication data
  
Flowchart of dementia cohort attached in this repository.

# Statistical Analysis (RStudio)
Descriptive statistics of the processed dataset

Logistic regression analysis to investigate the predictors associated with a 180-day hospital readmission

Cox regression analysis to investigate survival risk within one year of hospital readmission

Generation of statistical outputs and visualizations 





