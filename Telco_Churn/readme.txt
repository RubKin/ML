Telco Customer Churn Challenge

This project is create to analyse the behavior of customers and be able to predict the retainability in the company.

The Data was retrieved from https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Dataset Information

- 'customerID',           ID of the customer
- 'gender',               male or female
- 'SeniorCitizen',        1,0 if the customer is a senior
- 'Partner',              Yes, No  if they have a partner
- 'Dependents',           Yes, No  if they have a partner
- 'tenure',               Numerical, No of Months that the custmer has been in the company
- 'PhoneService',         Yes, No Wether the Customer has a phoneline
- 'MultipleLines',        Yes, No, No phone Service 
- 'InternetService',      DSL, Fiber Optic, No
- 'OnlineSecurity',       Yes, No, No Internet Service
- 'OnlineBackup',         'No', 'Yes', 'No internet service'
- 'DeviceProtection',     'No', 'Yes', 'No internet service'
- 'TechSupport',          'No', 'Yes', 'No internet service'
- 'StreamingTV',          'No', 'Yes', 'No internet service'
- 'StreamingMovies',      'No', 'Yes', 'No internet service'
- 'Contract',             'Month-to-month', 'One year', 'Two year'
- 'PaperlessBilling',     Yes, No
- 'PaymentMethod',        Electronic check', 'Mailed check', 'Bank transfer (automatic)','Credit card (automatic)'
- 'MonthlyCharges',       Numerical, charges per month
- 'TotalCharges',         Numerical, The charges of all the time the customer has been in the company
- 'Churn'                 Yes, No

Project Steps:

1. Overview and cleaning the dataset
    - check the main statistical information of the Dataset
    . look for missing values and fill them out or drop them
    - 

2. EDA
    -Check the correlation between the different features and the importancy of them

3. Feature Engeneering
    - Encode the features with onehot enconder
    - get rid of the unnecessary features

4. Modeling
    - first comes the anaylsis with Decision tree the further anaylse the dataset
    - since the Decision Tree model gives us overfitting and a lot of false positives and negatives we have to balance the dataset
    - To balance the dataset Smoteen is used
