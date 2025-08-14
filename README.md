# CKD-Data-Wrangling-Project
This Python project wrangles a Chronic Kidney Disease (CKD) dataset from Abu Dhabi EHRs using Pandas. It loads, cleans (handles missing values, duplicates, outliers), transforms (creates age groups, scales features), and exports the data for future analysis. No modeling or visualization.
Setup:





Save the dataset as ChronicKidneyDisease_EHRs_from_AbuDhabi.csv.



Install Python 3.x and Pandas (pip install pandas).



Run ckd_data_wrangling.py in a Python environment or Jupyter Notebook.

Files:





ckd_data_wrangling.py: Main script for data wrangling.



ChronicKidneyDisease_EHRs_from_AbuDhabi.csv: Input dataset.



ckd_wrangled.csv: Output cleaned and transformed dataset.



ckd_summary_by_sex_diabetes.csv: Summary of average eGFR by sex and diabetes history.

Usage: Run python ckd_data_wrangling.py to process the data. Outputs are saved as CSVs.

Requirements: See requirements.txt for dependencies.
