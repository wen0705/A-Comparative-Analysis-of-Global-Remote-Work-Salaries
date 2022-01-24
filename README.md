# Project2022

## Data:
In this project we mainly use two datasets:
- AI salaries from https://salaries.freshremote.work/download/salaries.csv
- world dataset from geo pandas "naturalearth_lowres"

## Data cleaning:
- world dataset: change the iso3 code of United States Minor Outlyng Islands and American Samoa in USA
- delete the  Singapore's data from salary dataset (Because there is no Singapore in world dataset)
- select the data which occurs both in year 2020 and 2021
- delete the job which do not use AI/ML skills

## Questions of the dataset:
1. Is there a difference in wage (same job but in different location)?
2. Which jobs earn more money?
3. Is remote ratio disparity in different countries?
4. Which job has a brighter future?
5. Is the difference between each experience level are huge? average job salary in USA and not USA countries are different
6. Which factor affect our salary?

## Answer of the question:
1. Faireness:
Wage discrimination/wage disparity: An equal wage for equal work that does not lead to wage discrimination and does not generate unjustified and high wage differentials within the company.
2. barplot
3. chorolepth map
4. slope data
5. hypothesis test
6. correlation map


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
