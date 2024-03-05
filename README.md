# Customer_Churn_Modelling

The report delves into an in-depth analysis of Telco customer churn, utilizing various data analysis and machine learning techniques. Here's a detailed summary:

Exploratory Data Analysis (EDA):

Initial examination of customer data, including demographics, service subscriptions, and contract details.
Checked for missing values and duplicate rows.
Histograms and boxplots created to visualize the distribution of categorical and numeric variables.
Data Preprocessing:

Converted categorical variables into numeric form using factorization.
Handled missing values in the 'TotalCharges' column by replacing them with the mean.
Dropped the 'customerID' column as it was not relevant for modeling.
Modeling:

Built a logistic regression model to predict churn.
Used various features like tenure, internet service, contract type, and monthly charges to predict churn.
Logistic regression model achieved a pseudo R-squared value of 0.2835 and an accuracy of 80.59% using a threshold of 0.5.
Tested the logistic regression model and a decision tree classifier on a test set.
Logistic regression model achieved an accuracy of 82.19%, while the decision tree classifier achieved an accuracy of 74.24%.
Conclusion:

The analysis provides valuable insights into factors influencing churn, such as contract type, tenure, and internet service.
The logistic regression model demonstrates robust predictive power in identifying potential churners.
Decision tree classifier offers an alternative approach, though with slightly lower accuracy.
These findings can inform Telco's customer retention strategies, potentially reducing churn rates and improving customer satisfaction.
