# CodeAlpha\_UnemploymentAnalysis

\# Unemployment Analysis with Python



CodeAlpha Data Science Internship, Task 2.



Analysis of monthly unemployment rate data for Indian states covering May 2019 to June 2020, spanning the period before and during the first national Covid-19 lockdown.



\## Data



`Unemployment in India.csv`, supplied by CodeAlpha. 768 rows on load, 740 after

cleaning, across 7 columns. Each row records one region, for one month, split by

rural or urban area, giving the unemployment rate, the number employed and the

labour participation rate.



\## What the notebook does



1\. Loads the raw file without modification

2\. Inspects it and documents three defects found: leading spaces in the column

&#x20;  names, dates stored as text, and 28 completely blank rows

3\. Cleans each defect and verifies the result

4\. Explores the data by region and by area

5\. Visualises the trend overall, split by area, and across regions

6\. Splits the series at 25 March 2020 to measure the effect of lockdown

7\. Tests whether seasonality can be assessed, and sets out the policy-relevant

&#x20;  findings



\## Findings



The national rate holds between 9.0% and 10.0% from May 2019 through February 2020, then rises to 23.6% in April 2020 and peaks near 24.9% in May, falling back to 11.9% by June.



Labour participation moves in the opposite direction, dropping 8.00 percentage points in April to 35.10%. Because unemployment counts only those actively seeking work, this means people were leaving the labour force rather than registering as unemployed, so the headline peak understates the disruption.



Regional effects vary widely and fall into two groups. Puducherry rose from 1.59% to 38.96% and Tamil Nadu from 2.84% to 25.40%, both from low bases. 

Jharkhand, Bihar and Haryana already carried double-digit unemployment before March 2020 and worsened from there. Ranking by percentage-point change places both on the same list, but they describe different problems.



Urban unemployment ran above rural throughout. The gap widened from around two percentage points before lockdown to close to seven at the May peak, then closed almost entirely in June.



No seasonal pattern is claimed. Only May and June appear in two different years, and both 2020 occurrences fall inside the lockdown period, so no normal year can be compared against another.



\## Limitations



Fourteen months is too short to establish trend or seasonality. The series ends in June 2020, so whether the recovery held is unknown. Regional averages are unweighted, meaning each state counts equally regardless of population, so the national figures are averages of regions rather than national totals.



\## Running it

Requires Python 3 with pandas, numpy, matplotlib and seaborn. Open unemployment\_analysis.ipynb` in Jupyter and run all cells in order.



\## Files



\- `unemployment\_analysis.ipynb` - the analysis

\- `Data/Unemployment in India.csv` - the dataset

\- `README.md` - this file



\## Author



Ahmed Yunus Albarka

