# Project2022

## Data:
In this project we mainly use two datasets:
- AI salaries from https://salaries.freshremote.work/download/salaries.csv
- world dataset from geo pandas "naturalearth_lowres"

### Downsides of the datasets:
- There is no Singapore, Malta, United States Minor Outlyng Islands, and American Samoa in the world dataset
- The jobs 'Cybersecurity Analyst' 'DevOps Architect' 'Machine Learning Engineer' and 'Linux Infrastructure Developer' are in the salary dataset 2020 but not in 2021

### How to solve this problem:
- we combine United States Minor Outlyng Islands, and American Samoa into USA and ignore the singapore and Malta
- We can only ignore them 

## Analysts:
1. Preprocessing: We make the correlation map and select the sensitive factors 
2. Faireness:
Wage discrimination/wage disparity: An equal wage for equal work that does not lead to wage discrimination and does not generate unjustified and high wage differentials within the company.







## Problem need to ask tutor
The primary problems we found out about the data:
  1. The data is not promising because some country data are missing
  2. The world data set lack some data of countries say Russia but which are present in the company location
  3. The percentage of remote ratio differes between two years. The years are categorized in 4 part (2020e, 2020, 2021e, 2021). we are missing data from several countries in 2021 but which are present in 2021e.
  4. How to deal with the salary?


fairness/hypothesis
