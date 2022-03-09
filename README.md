# Loan-Eligibility-Prediction

Loans are one of the most important sources of income for a bank. An intense procedure of verification and validation should be done before granting the loan to a candidate as the main profit comes directly from the loan’s interest.
Aim: To create a predictive model to predict the eligibility of an applicant for a loan.
Steps: 
- Observe and understand the data
- Exploratory data analysis
- Data preprocessing - missing values, encoding, outliers handling
- Data Visualization
- Model Selection
- Train the model
- Prediction of the model.  

Firstly, the necessary libraries are imported. The required data for the project is downloaded from Kaggle and is also provided in this repository. To understand the data, the describe method is used to show the important information about the features. The unique values for each column and other information is observed. 
To understand more about the data exploratory data analysis is performed. The values that each feature contains and the relation with the output is understood.  
To clean the data so that it is reliable, first the missing values in numeric features are filled with mean values, next the categorical features are encoded and then a similar procedure is used to fill missing values. The outliers are identified and those that are exceeding the lower and upper bounds are replaced with extreme values. Now all the features have numeric values and are clean.  
Data visualization tools are used to know how output relies on different features. Correlation function is also used to see if any two features are dependent on each other as well to recognize their relation with the output. The cleaned data is extracted to train and predict the model.  

As this is a binary classification problem support vector machine and linear regression models are used and performance metrices like accuracy score, confusion matrix, recall, precision, and roc curve are used to evaluate the model.
