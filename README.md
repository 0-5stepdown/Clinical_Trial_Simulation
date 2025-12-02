# Project Overview

In this project, I demonstrate my understanding of A/B test design and implementation by simulating a clinical experiment assessing the efficacy of a blood pressure medication.

See below description of project structure:

1. Design and define A/B test components
2. Set up statistical hypothesis test
3. Randomly sample hypertension patients for the experiment
4. Wrangle pre-medication patient data
5. Conduct exploratory data analysis
6. Implement random and independent assignment of patients to control vs. treatment group
7. Obtain post-medication patient data
8. Conduct statistical hypothesis test
9. Draw conclusions about the efficacy of the medication

# Data

Given that I do not have access to real-life clinical data, I generated the following synthetic datasets to replicate an experimental setting:

* Raw hypertension patient dataset before medication ([Link](https://github.com/0-5stepdown/Clinical_Trial_Simulation/blob/main/data/baseline_sbp_data.csv))
  * Features include **patient_id**, **age**, **sex**, **ethnicity**, and **baseline_sbp**.
  * This dataset incorporated various data issues such as missing data, duplicates, inconsistent feature labels, imbalanced demographic groups, and outlier blood pressure readings.   

* Wrangled hypertension patient dataset before medication ([Link](https://github.com/0-5stepdown/Clinical_Trial_Simulation/blob/main/data/baseline_sbp_clean_data.csv))
  * Data wrangling was done within the project workbook, then saved as a CSV file. 

* Random and independent assignment of patients to control vs. treatment group ([Link](https://github.com/0-5stepdown/Clinical_Trial_Simulation/blob/main/data/variants_data.csv))
  * Variant assignment was done within the project workbook, then saved as a CSV file.

* Hypertension patient dataset after medication ([Link](https://github.com/0-5stepdown/Clinical_Trial_Simulation/blob/main/data/post_sbp_data.csv))
  * This dataset incorporates occurrences of side effects and random variability in patient systolic blood pressure post-medication

The code used to generate the hypertension patient datasets before and after medication can be found at the link below:

[Code for generating synthetic datasets](https://nbviewer.org/github/0-5stepdown/Clinical_Trial_Simulation/blob/main/data/AB%20Testing%20-%20Blood%20Pressure%20Medication%20Data.ipynb)

# Project Workbook

Click link below to walk through the project workbook:

[AB Testing - Blood Pressure Medication](https://nbviewer.org/github/0-5stepdown/Clinical_Trial_Simulation/blob/main/code/AB%20Testing%20-%20Blood%20Pressure%20Medication.ipynb)
