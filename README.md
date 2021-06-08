# WalmartSalesPrediction
Predict weekly Walmart sales for Kaggle data https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/

# Problem Statement![image]

Walmart Inc. is the world’s largest company by revenue as well as the largest private employer and grocery retailer. 
Our aim is to accurately forecast weekly sales of Walmart as it helps its ability to function and provide employment. 

Dataset for the Problem!

The data set for our problem was obtained from Kaggle and it contains various departments within different stores over different period of time with several other features like store Size, store Type, Holiday, Date, Temperature, etc. to evaluate Weekly Sale of the store.

We are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and we must project the sales for each department in each store!


The data has :
Store as the primary key over which we have joined these tables 

 We had 45 Stores and at least 81 Departments under each store

 Weekly sales is the target variable 

![image](https://user-images.githubusercontent.com/60999947/121236901-74fdb180-c864-11eb-9230-6810c12882d0.png)


# Data exploration

% Store type 
![image](https://user-images.githubusercontent.com/60999947/121237055-a2e2f600-c864-11eb-8981-438c5f6c0d04.png)

Analysis of demand variability

![image](https://user-images.githubusercontent.com/60999947/121237201-ca39c300-c864-11eb-85b4-3f5e5df4a94d.png)

Major Holiday extraction!

![image](https://user-images.githubusercontent.com/60999947/121237265-dc1b6600-c864-11eb-81b2-1c530ece764a.png)


Machine learning models:

Data was split into train test partitions:

Different machine learning regression models were evaluated using Mean Absolute Error and R squared error.

Random forest with hyper parameter tuning performed best!

![image](https://user-images.githubusercontent.com/60999947/121237588-35839500-c865-11eb-88bf-0ad4c8bf3acc.png)



1. 
