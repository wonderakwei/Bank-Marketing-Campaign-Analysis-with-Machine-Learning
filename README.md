# Bank Marketing Campaign Analysis with Machine Learning

## About the Dataset

### Context
This project focuses on identifying optimal strategies to enhance the effectiveness of future marketing campaigns for a financial institution. By analyzing the patterns from the last marketing campaign, the goal is to provide insights and develop data-driven strategies for future endeavors.

### Source
[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014.

## Introduction
In this project, we analyze the results of a past marketing campaign to uncover patterns and strategies for improving future campaigns' effectiveness. The business objective is to increase the Return on Investment (ROI) of upcoming marketing efforts. Our approach involves using machine learning techniques, specifically visualizing data, employing a LightGBM model for predictions, and interpreting results using the SHAP library.

## Project Overview
1. **Data Exploration**: Visualize and understand patterns and trends in the campaign results.
2. **Machine Learning Model**: Utilize LightGBM for predicting campaign effectiveness.
3. **Interpretation**: Understand and interpret model predictions using the SHAP library.

## Attribute Descriptions
### Bank Client Data:
1. `age`: Numeric, client's age.
2. `job`: Categorical, type of job.
3. `marital`: Categorical, marital status.
4. `education`: Categorical, educational level.
5. `default`: Categorical, credit in default.
6. `housing`: Categorical, housing loan status.
7. `loan`: Categorical, personal loan status.
8. `balance`: Numeric, individual's balance.

### Related to Last Contact:
9. `contact`: Categorical, communication type.
10. `month`: Categorical, last contact month.
11. `day`: Last contact day of the week.
12. `duration`: Numeric, last contact duration (seconds).

### Other Attributes:
13. `campaign`: Numeric, number of contacts during this campaign.
14. `pdays`: Numeric, days since last contact from a previous campaign.
15. `previous`: Numeric, number of contacts before this campaign.
16. `poutcome`: Categorical, outcome of the previous marketing campaign.

### Output Variable (Target):
17. `y`: Binary, subscription to a term deposit ('yes' or 'no').

## Project Goal
Provide insights into the past campaign's performance and make data-driven decisions to enhance the financial institution's effectiveness in future marketing campaigns.
