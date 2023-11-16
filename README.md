# Customer Profiling and Attrition Prediction

## Overview
This project aims to analyze customer data from a consumer credit card portfolio to understand customer demographics, spending habits, and their relationship with the credit card provider. The ultimate goal is to predict customer attrition (churn) and develop customer personas that can help tailor services to specific customer groups.

## Dataset
The dataset used for this analysis contains comprehensive customer information, including demographic details (age, gender, marital status, education level, and income category), financial metrics (credit limit, revolving balance, utilization ratio), and attrition flags. It provides valuable insights into customer behavior leading up to churn decisions.

## Exploratory Data Analysis (EDA)
- Conducted initial data exploration to understand the dataset's characteristics, including data types, missing values, and summary statistics.
- Handled missing values and encoded categorical variables for analysis.
- Selected relevant features, such as age, income category, credit limit, total revolving balance, and utilization ratio.
- Explored relationships between customer demographics and attrition rates using visualizations, including box plots, count plots, and scatter plots.

![customer age ](https://github.com/rimchristian/Customer-Segmentation-/assets/74616874/a60f0bf5-5fa8-411e-aaa5-77674e8e22a1)

![income](https://github.com/rimchristian/Customer-Segmentation-/assets/74616874/56e20a27-2cb9-4010-8597-9fff0555be5e)

![credit](https://github.com/rimchristian/Customer-Segmentation-/assets/74616874/902e1d58-e7ce-43cc-9a42-d6ab0a9bd967)

![util](https://github.com/rimchristian/Customer-Segmentation-/assets/74616874/c993398c-e32a-497d-be31-c70d53fb9c40)

![edu](https://github.com/rimchristian/Customer-Segmentation-/assets/74616874/8088b766-b7ae-4469-95b8-243af4702fb9)

![card](https://github.com/rimchristian/Customer-Segmentation-/assets/74616874/f4fba38e-59a7-4e58-b6c9-be512726bbd1)


## Machine Learning for Attrition Prediction
- Built a Random Forest Classifier to predict customer attrition based on selected features.
- Achieved an accuracy of 85% on the test set.
- Evaluated the model's performance using classification metrics, including precision, recall, and F1-score.
- Used cluster analysis to group customers into distinct segments.
  
![cluster](https://github.com/rimchristian/Customer-Segmentation-/assets/74616874/d670c7da-5295-4505-8209-4bb99753802d)


## Customer Profiling and Persona Development
- Analyzed the impact of different customer characteristics on attrition rates.
- Explored how age, income category, credit limit, revolving balance, and utilization ratio relate to attrition.
- Identified distinct customer personas based on attrition risk and characteristics.
- Developed personas, including descriptions of each group, to guide marketing and retention strategies.




## Recommendations
- Provided actionable recommendations for the credit card provider based on the analysis and personas.
- Suggested tailored marketing campaigns and retention strategies for specific customer segments.
- Highlighted key insights into customer behavior and attrition risk factors.

1. Persona 1: "Young Professionals"
Age: 25-35
Income category: High
Credit Limit: Moderate
Total Resolving Balance: Low
Utilization Ratio: Low
Attrition Risk: Low
Description: Young professionals with high incomes and responsible credit card usage. Low Attrition risk
2. Persona 2: Mature Savers
Age: 40-55
Income category: Moderate
Credit Limit: High
Total Resolving Balance: Low
Utilization Ratio: Low
Attrition Risk: Very Low
Description: Middle-age customers with moderate incomes and low credit card usage. Very low attrition risk.
3. Persona 3: "Credit Card Enthusiasts"
Age: 30-45 years
Income Category: Moderate
Credit Limit: High
Total Revolving Balance: Moderate
Utilization Ratio: Moderate
Attrition Risk: Moderate
Description: Customers who actively use their credit cards but maintain moderate balances. Moderate attrition risk.



## Conclusion 
This Customer Profiling and Attrition Prediction project offers valuable insights into customer behavior within a credit card portfolio. By analyzing demographics, financial metrics, and attrition rates, we can help the credit card provider make informed decisions and tailor their services to better serve their customers.




