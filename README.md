# Healthcare Analytics for Doctor Visits

Data analytics project completed as part of the Edunet Foundation programme.

## Objective
Identify which personal, health, financial and healthcare-support factors are associated with the number of doctor visits.

## Dataset
5,190 patient records with 12 features: visits, gender, age, income, illness, reduced, health, private, freepoor, freerepat, nchronic, lchronic.

## Approach
- Data cleaning and understanding
- Exploratory data analysis with visualisations
- Statistical testing (Mann-Whitney U)
- Poisson regression, Random Forest regression and classification
- Patient risk segmentation

## Key Findings
- About 80% of people had no doctor visit.
- Days of reduced activity and number of illnesses are the strongest predictors of visits.
- Visits increase with age; women visit more than men.
- Private insurance shows no significant effect.
- High-risk patients average about 7x more visits than low-risk patients.

## Files
- `Healthcare_Analytics_for_Doctor_Visits.ipynb` : full analysis notebook
- `1776250375-P2-Healthcare_Analytics_for_Doctor_Visits.csv` : dataset

## Tools
Python, pandas, NumPy, matplotlib, seaborn, SciPy, statsmodels, scikit-learn
