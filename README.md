# Loan Default Prediction with ML

## Project Overview
This project focused on analyzing loan data to predict default status and understand key factors influencing loan outcomes. The workflow included:

1. **Data Cleaning and Preprocessing**: Addressed missing values, standardized data types, and created new features like AGE_GROUP.
2. **Exploratory Data Analysis**: Examined distributions and relationships between variables through visualizations.
3. **Statistical Analysis**: Performed chi-square tests and t-tests to identify significant relationships.
4. **Model Development**: Trained and evaluated Decision Tree and Random Forest models.

## Key Findings
- The Random Forest model achieved superior performance with higher accuracy and better precision/recall balance.
- Financial indicators (NET INCOME, PRINCIPAL_DISBURSED) were the strongest predictors of loan default.
- Demographic factors like AGE and MARITAL_STATUS also significantly influenced default risk.
- PRUDENTIAL_CLASSIFICATION showed the strongest association with default status based on chi-square tests.

## Recommendations
1. **Risk Assessment Enhancement**: Implement the Random Forest model to improve default prediction accuracy.
2. **Targeted Product Development**: Design loan products tailored to different risk profiles based on the identified key factors.
3. **Customer Segmentation**: Use the insights from demographic analysis to better segment customers and offer appropriate financial products.
4. **Process Optimization**: Focus verification efforts on the most influential factors to streamline the loan approval process.
