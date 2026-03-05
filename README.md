# Poloko-Assignment-Project-1
Loan Default Risk — EDA & Baseline Model
Exploratory Data Analysis and logistic regression baseline on a dataset of 252,000 Indian loan applicants to understand what drives credit default.

Dataset

Source: CSEdata.csv
Records: 252,000 borrowers
Target: Risk_Flag (1 = Default, 0 = No Default)
Default Rate: 12.3%


What This Project Does

EDA — Tests 7 hypotheses about what causes loan default, with visualisations for each
Data Cleaning — Fixes inconsistencies, removes low-value columns, and encodes categoricals
Feature Selection — Identifies the 8 most predictive features using correlation, mutual information
Model Evaluation — Trains and evaluates a logistic regression baseline with full metrics


Key Findings

Job tenure is the strongest predictor — borrowers in their 1st–2nd year at a new employer default nearly 40% above average
Income is surprisingly weak — default rates are flat across all income quartiles
Profession matters — default rates range from 8.1% (Technology Specialists) to 16.4% (Police Officers)
Homeowners default at 9.0% vs 12.6% for renters
Geography plays a role — Kerala and Madhya Pradesh have the highest state-level default rates
