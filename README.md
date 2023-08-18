# Customer churn

Beta Bank started losing customers. Every month. Not many, but noticeable. Bank marketers have calculated that it is cheaper to keep current clients than to attract new ones.

Let's make a forecast whether the client will leave the bank in the near future or not. You are given historical data on customer behavior and termination of contracts with the bank. 

Let's build a model with an extremely large value of *F1*-measure. We need to bring the metric to 0.59. Let's check *F1*-measure on the test sample independently.

In addition, we measure *AUC-ROC* and compare its value with *F1*-measure.

Data source: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

 ## Data description
The data is in the file /datasets/Churn.csv. 

**References**
 - RowNumber - row index in the data
 - CustomerId - unique identifier of the customer
 - Surname - last name
 - CreditScore - credit rating
 - Geography - country of residence
 - Gender - sex
 - Age - age
 - Tenure - amount of real estate owned by the client
 - Balance - account balance
 - NumOfProducts - number of bank products used by the client
 - HasCrCard - availability of credit card
 - IsActiveMember - client's activity
 - EstimatedSalary - estimated salary
 
**Target attribute**
 - Exited - the fact of client's leaving