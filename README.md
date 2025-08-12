Exploring Patterns in Synthetic Asthma Clinical Data
🎯 Objective
This project aims to analyze synthetic clinical data to identify demographic, clinical, and behavioral patterns associated with asthma. Using Python-based data analytics, statistical testing, and visualization techniques, we explore correlations between asthma diagnosis and variables such as age, gender, comorbidities, and medication use.

📂 Dataset
Name: Synthetic Asthma Dataset

Source: [Synthetic Health Data Generator]

Description: Contains anonymized and synthetically generated patient-level data with fields such as:

Age, Gender, Ethnicity

Has Asthma (yes/no)

Comorbidities (e.g., diabetes, hypertension)

Number of hospital visits

Medications

Insurance and socioeconomic indicators

🧹 Steps Performed
✅ 1. Data Cleaning & Preprocessing
Removed duplicates and missing values

Handled date and categorical type conversion

Cleaned comorbidity and medication fields

✅ 2. Univariate Analysis
Most patients were in the 25–50 age range

Gender distribution was balanced

Hypertension and obesity were frequent comorbidities

About 30–40% had asthma in the dataset

✅ 3. Bivariate Analysis
Higher asthma prevalence in patients with comorbid conditions

Males had slightly higher asthma rates

Older patients had a higher likelihood of asthma

✅ 4. Statistical Hypothesis Testing
Chi-Square Test: Showed significant association between gender and asthma (p < 0.05)

T-Test: Mean age of asthma patients was significantly higher than non-asthmatics (p < 0.05)

Mann–Whitney U Test: Confirmed age differences when distributional assumptions weren't met

📈 Visualization Techniques
Used matplotlib, seaborn, and pandas to create:

Bar plots (gender, comorbidities)

Histograms (age distribution)

Boxplots (age by asthma status)

Heatmaps (correlation matrix)

Key Insights
Asthma is more prevalent among older patients and those with chronic comorbidities like hypertension and diabetes.

There is a statistically significant difference in asthma prevalence between genders and across age groups.

Preventive care strategies can be informed by identifying high-risk demographics.

