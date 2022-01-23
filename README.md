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
Question:

1 Fairness:
We want to study the wage disparity among different countries:
e.g. The payment of full-time junior-level Data Scientists in the US and DE
Do you think it is worth analysis or do it belong to a fairness problem

2 t-test:
We have done a t-test to study the average-salary difference between the USA and non-USA countries in each experience level.
However, we get a small p-value like 3 x e-06.
Do you think it is meaningful to do this test? Because our dataset is problematics. Some full-time jobs only appeared in the year 2020. And after filtering, we only have 14 jobs in both years 2020 and 2021(and yes, with different experience levels)

3 Correlation heatmap:
3.1 We change the string to integer: e.g. company size from {S M L} to {1,2,3}.
Do you think it is the right way to convert the data and see the correlation between these attributes?
3.2
Based on the correlation map(the correlation heatmap is attached) we figure out that everything is correlated. We just notice the strong correlation (0.45) and ignore the weaker one (like 0.12). Do you think it is right to do this?


4 What else can we do?
We have already done the Choropleth maps about remote ratio and a hypothesis test. We need some ideas about analysis and how to do that. Right now, we do not think we can get any meaningful or surprising conclusions from our maps and analysis.

5 We put everything in GitHub (including the questions), but our repository is private. If it is possible to give us your GitHub username?  We can then add it, and you can see our progress directly. 
