# Customer Churn Analysis using Logistic Regression
![Customer-Churn](https://github.com/sangjun927/customer-churn-analysis/assets/36908657/a563b8f2-da9b-4d9c-8dce-03313e787e45)

## Project Overview
This project, undertaken as part of the MSDS 601 course at the University of San Francisco, focuses on analyzing customer churn for a California-based Telco company. The aim is to understand the factors influencing churn and devise strategies to reduce the churn rate by at least 10% by year-end.

## Introduction
Customer churn, a vital metric for business sustainability, especially in the telecom sector, signifies the loss of clients or customers. In response to a 15% increase in churn rate after Q3, this study utilizes a data-driven approach to mitigate customer attrition.

## Dataset Overview
- **Source:** Kaggle-Telco-Customer-Churn and IBM Community
- **Composition:** 7043 observations across 33 attributes, encompassing demographic, service, and financial data
- **Significant Attributes:** 'Churn Label' as the dependent variable and various customer-related features as independent variables
- **Preprocessing:** Conversion of data types and handling of missing values, particularly in the 'Churn Reason' attribute

## Exploratory Data Analysis (EDA)
- **Geographical Influence:** Heatmap analysis revealed higher churn rates in major cities like Los Angeles, San Francisco, and San Jose.
- **Numerical Data Insights:** Strong correlation of 'Churn Value' with 'Churn Score' and 'Tenure Months'
- **Categorical Data Analysis:** Crossplots highlighted the impact of contract type on churn, with month-to-month contracts showing higher churn rates.

## Regression Analysis
Logistic regression was employed to model the probability of churn, considering over 30 features, including demographics, service usage, and geographical data.

## Model Diagnosis and Selection
- **Challenges:** Addressed multicollinearity and influential data points to refine the model
- **Final Model Selection:** Based on Recall score, the reduced model (0.85) outperformed the full model (0.828), leading to its selection for further analysis

## Key Findings
- Factors such as senior citizen status, phone service, contract length, and payment method significantly affect churn probabilities.
- Each additional month of tenure and certain payment methods notably decrease the odds of churning.

## Recommendations
1. **Senior Citizen Engagement:** Implement targeted strategies to retain senior citizens.
2. **Phone Service Enhancement:** Improve and promote phone service features.
3. **Contract Length Optimization:** Encourage longer contract terms.
4. **Payment Method Diversification:** Offer incentives for preferred payment methods.
5. **Churn Score Monitoring:** Regularly evaluate churn scores to identify at-risk customers.

## Conclusion
This analysis provides actionable insights into reducing customer churn, emphasizing the need for tailored strategies to enhance customer retention and satisfaction.

## References
- [Kaggle Dataset](https://www.kaggle.com/datasets/ylchang/telco-customer-churn-1113)
- [IBM Community](https://community.ibm.com/community/user/blogs/steven-macko/2019/07/11/telco-customer-churn-1113)
