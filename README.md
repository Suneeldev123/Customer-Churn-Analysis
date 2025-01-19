# Customer-Churn-Analysis
Analyze customer churn behavior using the Telco Customer Churn dataset to uncover trends, answer business queries, and provide actionable insights for improving retention. 

## Project Overview
This project focuses on analyzing customer churn data to uncover patterns, trends, and actionable insights. The analysis is divided into the following steps:
1. Data cleaning to prepare the dataset for analysis.
2. Exploratory Data Analysis (EDA) using graphs and statistical summaries.
3. Addressing key business questions with data-driven insights.

## Dataset
The dataset includes customer demographics, usage behavior, subscription details, and churn information.

## Introduction
Customer churn, also known as customer attrition, refers to the loss of customers over a given period. This metric is critical for businesses as retaining existing customers is often more cost-effective than acquiring new ones. The ability to analyze churn behavior helps organizations identify the factors contributing to churn and implement targeted strategies to improve customer retention.

In this project, we analyze the **Telco Customer Churn dataset**, which contains information about customers' demographics, account details, and service usage. By examining patterns in the dataset, we aim to uncover key drivers of churn and provide actionable insights for businesses to mitigate this issue.

### Objectives
1. **Understand churn behavior**: Analyze customer demographics, subscription details, and service usage to identify trends and correlations.
2. **Visualize churn patterns**: Use statistical summaries and visualizations to highlight the most significant features affecting churn.
3. **Answer business questions**: Address specific queries related to customer behavior, subscription types, and service impact.
4. **Provide actionable insights**: Offer recommendations based on findings to guide business strategies for reducing churn.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn

## Steps in the Analysis
1. **Data Cleaning**: 
   - Removing duplicates, handling missing values, and standardizing column names.
   - Replacing blank values in `TotalCharges` with `0` and converting the column to a numeric type.
   - Converting the `SeniorCitizen` column to 'Yes' and 'No' for better readability.
   - Transforming the `Churn` column from 'Yes'/'No' to numerical values (`1` for churn, `0` for non-churn).
2. **EDA**:
   - Churn distribution analysis.
   - Correlation heatmap.
   - Trends across features like tenure, monthly charges, and total charges.

## Visualizations
- Distribution of churn and non-churn customers.
- Heatmap showing correlations between features.
- Histograms and bar plots of key features segmented by churn.

## Summarized Findings
1. Senior citizens have a high churn rate (41.7%), making them a key demographic for retention efforts.
2. Customers on month-to-month contracts exhibit significantly higher churn (42.7%), while longer-term contracts drastically reduce churn.
3. Cost-sensitive customers, identified by higher monthly charges ($74.44), churn more frequently than those paying lower monthly charges ($61.27).
4. Customers with shorter tenure (average of 18 months) are much more likely to churn than long-term customers (average of 38 months).
5. Streaming services and phone service bundling show potential for retention, as customers without these services have slightly higher churn rates.
6. Paperless billing is linked to higher churn (33.6%), highlighting the need for enhanced customer engagement for digital-only users.
7. Automated payment methods like credit cards (15.2% churn) and bank transfers (16.7% churn) are associated with lower churn compared to electronic checks (45.3%).
8. Fiber optic internet has the highest churn rate (41.9%), indicating potential service quality or cost concerns.

## Recommendations
1. **Focus on Senior Citizens**: Offer senior-specific plans or discounts to cater to this demographic's unique needs and reduce their churn rate.
2. **Promote Long-Term Contracts**: Incentivize customers to switch from month-to-month contracts to one- or two-year contracts by offering discounts or added benefits.
3. **Address Cost-Sensitive Customers**: Introduce flexible pricing or discount plans for customers with high monthly charges, as these customers show a higher churn rate.
4. **Improve Retention of New Customers**: Focus on customers in their early tenure (less than 18 months) through onboarding programs, loyalty rewards, and personalized communication to reduce churn.
5. **Encourage Bundled Services**: Promote bundled streaming and phone services to enhance perceived value and engagement, reducing churn in customers without these services.
6. **Enhance Paperless Billing Experience**: Provide reminders and seamless payment experiences for customers using paperless billing, as they exhibit a significantly higher churn rate.
7. **Improve Fiber Optic Service Quality**: Address service issues for fiber optic customers, who have the highest churn rate, to improve satisfaction and retention.
8. **Promote Automated Payment Methods**: Encourage customers to switch to automated payment methods (bank transfers or credit cards), as these are associated with the lowest churn rates.

## Conclusion
This analysis demonstrates that customer churn is influenced by multiple factors, including contract type, monthly charges, tenure, and additional services. By addressing these factors with targeted strategies, businesses can reduce churn and improve customer retention. The insights gained from this project provide a strong foundation for implementing data-driven retention programs.
