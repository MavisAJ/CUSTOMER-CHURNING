# TELCO CUSTOMER-CHURNING
![Screen Shot 2022-11-16 at 1 37 51 PM](https://user-images.githubusercontent.com/105258546/202196361-6e49c83d-9beb-430c-9acd-efa1f5dff47b.png)


Customer churning refers to the percentage of customers that stopped using a company's products or services within a specified timeframe.
The aim of this project is to find the likelihood of a customer leaving an organization, the key indicators of churn as well as the retention strategies 
that can be implemented to avert this problem.Classification machine learning models in python are built and the best performing model selected to predict 
a customers likelihood of churning.

Implementation

Few glimpses of EDA showing the ratio of customers who churned to those who did not:

1. Churn by customers by internet services
![image](https://user-images.githubusercontent.com/105258546/202207015-2efbae09-5e1c-4861-8682-fe0a3d9c6fb1.png)
![image](https://user-images.githubusercontent.com/105258546/202207083-67e27cf7-45f6-4923-9e23-7edd43d629ad.png)

2. Churn by customers by dependants and partners
![image](https://user-images.githubusercontent.com/105258546/202216647-1445d03e-d33c-4d8e-964d-ab68b64a8e4c.png)

3. Churn by charges

![image](https://user-images.githubusercontent.com/105258546/202219996-99120f29-4f73-4625-8575-3d74a31a50e1.png)

4. Churn by senior and non-senior citizens
![image](https://user-images.githubusercontent.com/105258546/202219701-bf9e1562-2447-45c3-a6e7-609b43492966.png)

5. Churn by contract

![image](https://user-images.githubusercontent.com/105258546/202221547-57ca060f-34c8-4d5b-889d-c4c321f8f6f1.png)

6. Churn by paperless billings
![image](https://user-images.githubusercontent.com/105258546/202226019-9499fa47-85b8-4bf1-9c1b-134c819c2467.png)

7.Churn by tenure
![image](https://user-images.githubusercontent.com/105258546/202226667-2ca0a707-e9dd-4e83-8b37-efebdc0f6c41.png)

FEATURE ENGINEERING 

The Sklearn one-hot encoding was used to encoding all the cartegorical variables except the churn variable and all first cartegories dropped to
avoid dummy variable trap

SCALING 
All numerical columns where scaled 

Hyperparameter Tuning and Cross-Validation

Model was tuned using both the grid search and randomised search cv to improve model performance and cross-validated to view 
the model ability to generalise
Prediction
Model was prediction accuracy was 80.3%


Modeling

Five models were built and the best model being the random forest was selected.



