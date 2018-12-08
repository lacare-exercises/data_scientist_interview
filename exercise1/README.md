# Exercise 1 - Development of a Supervised Model

## Instructions
1. Download and use the ‘loan.csv’ data from this [location](https://kaggle.com/wendykan/lending-club-loan-data/downloads/lending-club-loan-data.zip).
2. Filter the “loan_status” variable to only contain “Charged Off” and “Fully Paid”.
3. Using the “loan_status” variable as the outcome and spliting the data into train and test sets, use the other variables below to develop the most appropriate type of classification model with the train dataset that predicts whether the `loan_status` should be “Charged Off” or “Fully Paid” on the test dataset. 
4. Exploratory analysis, model development, and model performance metric(s) are left to the discretion of the applicant.
5. Email the final script to Jamessa Jones.

Predictor variables to be considered for training the model:
```
"dti",
"annual_inc",
"delinq_2yrs",
"inq_last_6mths",
"open_acc",
"pub_rec",
"revol_bal",
"revol_util",
"total_acc",
"out_prncp",
"out_prncp_inv",
"total_pymnt",
"total_pymnt_inv",
"total_rec_prncp",
"total_rec_int",
"total_rec_late_fee",
"recoveries",
"collection_recovery_fee",
"last_pymnt_amnt",
"collections_12_mths_ex_med",
"loan_status",
"purpose",
"home_ownership",
"grade",
"emp_length",
"term",
"addr_state",
"verification_status",
"application_type"
```

## Assessment
The script developed by the applicant will be assessesd for:
- Data pre-processing
- Model selection and development
- Interpretation of model performance

 
