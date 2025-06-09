# MIMIC-III Clinical Dataset Visualization

This project explores key factors influencing patient outcomes and resource utilization within the MIMIC-III (Medical Information Mart for Intensive Care) dataset. Through a series of data visualizations, this analysis uncovers valuable insights into potential health disparities and identifies areas for improvement in healthcare delivery.

## Description

The analysis examines mortality rates, ICU stays, readmissions, medication prescriptions, and healthcare services across various patient demographics and clinical conditions. By visualizing these aspects, the project aims to identify patterns and correlations that can inform better healthcare strategies.

## Visualizations & Key Insights

### 1. Mortality Rate by Ethnicity and Insurance
This visualization indicates potential disparities in mortality rates among different ethnic groups and insurance types. Some ethnic groups appear to have higher mortality rates, and certain insurance types may be linked to higher mortality.

### 2. ICU Stay Duration by Top 10 Diagnoses and Gender
The data suggests potential differences in ICU stay durations between males and females for various diagnoses. Certain conditions, like respiratory failure and congestive heart failure, often lead to longer stays.

### 3. Readmission Rates by Discharge Location
This visualization shows that readmission rates differ significantly based on where a patient is discharged. Patients discharged to "OTHER FACILITY" and "DISTINCT PART HOSP" have notably higher readmission rates, suggesting that discharge location plays a crucial role in patient outcomes.

### 4. Medication Prescriptions by Gender and Age Group
This heatmap illustrates the distribution of medication prescriptions across different age groups and genders. Medication usage significantly increases with age for both males and females, with the highest percentage of prescriptions in the 60+ age group.

### 5. Healthcare Services by Age Group and Gender
This visualization breaks down the top 10 healthcare services used by males and females across different age groups. "MED" services are the most frequently used across all categories, while "TRAUM" services are more prevalent among younger males.

## Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly

## How to Run
1.  Clone the repository.
2.  Install the required libraries: `pip install pandas numpy matplotlib seaborn plotly`
3.  Download the MIMIC-III dataset and place the `.csv.gz` files in the project directory.
4.  Open and run the `MIMIC_III_Data_Visualization.ipynb` notebook in a Jupyter environment.

