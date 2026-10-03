# Hospital Readmission Analysis

## Project Overview

Hospital readmissions are an important indicator of healthcare utilization and patient outcomes. This project analyzes hospital encounter data for patients with diabetes to explore patterns associated with hospital readmission.

The analysis focuses on patient demographics, hospital utilization, clinical characteristics, and previous healthcare encounters to identify factors associated with 30-day readmission.

The project uses Python for data cleaning, exploratory data analysis, and visualization.

## Project Objective

The objective of this project is to explore patterns associated with hospital readmission among patients with diabetes and identify factors that may be useful for understanding readmission risk.

The analysis examines questions such as:

- Are patients with longer hospital stays more likely to be readmitted?
- Do patients with more medications or diagnoses have higher readmission rates?
- Is previous inpatient or emergency department utilization associated with readmission?
- How does 30-day readmission vary across age groups, medical specialties, race, and gender?
- Which patient and healthcare utilization characteristics appear most strongly associated with readmission?

## Dataset

This project uses the Diabetes 130-US Hospitals dataset, which contains hospital encounter records for patients diagnosed with diabetes across 130 U.S. hospitals.

The dataset includes information about:

- Patient demographics such as age, gender, and race
- Admission and discharge information
- Length of hospital stay
- Number of laboratory procedures and medications
- Number of diagnoses
- Previous inpatient, outpatient, and emergency visits
- Medical specialty
- Diabetes-related treatment information
- Hospital readmission status

The readmission variable categorizes encounters as:

- `<30` — readmitted within 30 days
- `>30` — readmitted after 30 days
- `NO` — no recorded readmission

## Tools & Technologies

- **Python** — data analysis and exploratory data analysis
- **Pandas** — data manipulation, aggregation, and analysis
- **Matplotlib** — data visualization
- **Jupyter Notebook** — interactive analysis and documentation
- **VS Code** — development environment
- **Git & GitHub** — version control and project documentation

## Analysis Performed

The exploratory data analysis investigates several factors that may be associated with hospital readmission, including:

- Overall hospital readmission patterns
- Length of hospital stay and readmission
- Number of laboratory procedures and readmission
- Number of medications and readmission
- Number of diagnoses and readmission
- Readmission rates across age groups
- Previous inpatient visits and readmission
- Previous emergency department visits and readmission
- 30-day readmission rates by medical specialty
- 30-day readmission rates by race
- 30-day readmission rates by gender
- Average length of hospital stay by age group
- Correlations among numerical healthcare utilization variables

## Key Findings

- Approximately 11% of hospital encounters resulted in readmission within 30 days.
- Patients readmitted within 30 days underwent the highest average number of laboratory procedures (44.23), compared with 42.38 among patients who were not readmitted.
- Patients readmitted within 30 days received an average of 16.90 medications, compared with 15.67 among patients who were not readmitted.
- Patients who were readmitted had a higher average number of diagnoses than those who were not readmitted.
- Previous hospital utilization showed a clear relationship with readmission. Patients readmitted within 30 days averaged 1.22 previous inpatient visits, compared with 0.38 among patients who were not readmitted.
- Patients readmitted within 30 days also had more previous emergency department visits on average (0.36) than patients who were not readmitted (0.11).
- Older patients generally experienced longer hospital stays, with patients aged 80–90 having the highest average length of stay at approximately 4.8 days.
- Among the most common medical specialties analyzed, Oncology showed the highest 30-day readmission rate.
- Readmission rates were relatively similar across gender and racial groups, suggesting that healthcare utilization and clinical characteristics may be more informative indicators of readmission in this dataset.

## Recommendations

Based on the exploratory findings, healthcare organizations could consider:

- **Prioritizing patients with frequent previous hospitalizations** for enhanced discharge planning and post-discharge follow-up, as prior inpatient utilization was strongly associated with readmission.
- **Monitoring patients with frequent emergency department utilization**, since these patients showed higher levels of subsequent readmission.
- **Providing additional support for patients with complex care needs**, particularly those with multiple diagnoses, medications, and laboratory procedures.
- **Strengthening transitional care for older patients**, who generally experienced longer hospital stays and may require additional coordination following discharge.
- **Investigating high-readmission specialties more closely**, particularly Oncology and other specialties with elevated 30-day readmission rates, to identify specialty-specific opportunities for improvement.

These findings represent associations observed in the dataset and should not be interpreted as evidence that these factors directly cause hospital readmission.

## Data Source & Attribution

This project uses the **Diabetes 130-US Hospitals for Years 1999–2008** dataset from the UCI Machine Learning Repository.

**Dataset citation:**  
Clore, J., Cios, K., DeShazo, J., & Strack, B. (2014). *Diabetes 130-US Hospitals for Years 1999–2008* [Dataset]. UCI Machine Learning Repository.

**DOI:** 10.24432/C5230J

The dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

