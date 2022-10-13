# Forecasting the leave of a Beta-Bank client.

## Research description: 
Identify the model that most accurately predicts customer leave.

## Research purpose: 
Build machine learning models, validate the parameters, test the prediction with the f1 metric and find the best option, improve the result by balancing the initial data.

## Research objectives:

- Examine input data,
- Split data into training, validation and test sets,
- Explore balance of classes,
- Train models without class balancing on:
- Decision Tree Classifier,
- Random Forest Classifier,
- Logistic Regression ,
 Balance classes with:
- Class weights,
- Upsample ,
- Downsample
Test data against test set. 
## Data: 
### Features:
- RowNumber - row index in the data
- CustomerId — unique customer identifier
- Surname - surname
- CreditScore - credit rating
- Geography - country of residence
- Gender - gender
- Age - age
- Tenure - how many years a person has been a client of the bank
- Balance - account balance
- NumOfProducts - the number of bank products used by the client
- HasCrCard - the presence of a credit card
- IsActiveMember - client activity
- EstimatedSalary - estimated salary 
### Target:
- Exited — the fact that the client has left

