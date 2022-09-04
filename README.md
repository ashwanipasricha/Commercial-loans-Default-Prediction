# Commercial loans Default Prediction

A commercial lending bank wants to identify obligers/customers who are at risk of defaulting on their loans in next 1 year. They are providing you with ~5000 customer’s financial data for past few years which includes ~200 companies that defaulted.

Along with the target variable, which talks about whether the customer has defaulted or not, there are other variables (predictor) like afterTaxInterestRate, taxRate, netValuePerShare, revenuePerShare etc

For more information, refer to file Tag_Description. 

# Solution:

I have followed this process to find the solution:

1. Get an understanding of the data (Missing values, data types, outliers etc.)
2. Perform an exhaustive Exploratory Data Analysis (EDA) and treat the outliers if any.
3. Build generalizable ML models to predict the probability of default, tune it and choose the best model.
4. Explain best model using any one of the available tools for explanability? (PDP, Shapley, Lime etc.)
