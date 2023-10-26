Fraud Detection model based on  credit card users information.

In this project, we will analyse customer-level data which has been collected from 3rd party. so don't worry I want to share the dataset with you and you can get it from here:

## Project Overview:
![image](https://github.com/yashpuraswani/Credit-Card-Fraud-Customer-Detection/assets/76052630/af39b3f1-aa42-4f03-9fc9-3dc02d910d22)

Using Pandas library I loaded the dataset and also check the complete information about the dataset using the same library.
since the data is having lot of Null values I am going to take help of statistics concept to clean the data and if my approach was not a good way for doing this Project Please let know.
But while focusing on Missing values I got it know Last 2 rows are completely NAN so I removed the last 2 Rows.

yah After removing last 2 rows the data becomes quite good where only 2 columns having null values and remaining things are solved:


## I am following Machine Learning pipeline for developing this project :

           - PipeLine of Machine Learning Project:
           - Collect the data
           - check the data information
           - split the data
           - training operations should be done on test data [Just Keep in Mind]
           - Handle Missing values if There
           - Checking Normal Distribution
           - Checking Outliers
           - Handling them
           - Handle Cateogorical data
           - Transformation Techniques
           - Scaling 
           - select best features for both numerical and categorical data
           - checking data balance or not
           - Model developement
           - check validation
           - Evaluate model
           - check AUC and ROC For selecting Best Model
           - Save the model
           - Read the Model and check once again
      

## why spliting the data:

If we divide the data after feature engineering part the std[standard deviation and variance] will be completely different for both train and test this leads to data leakage, so to overcome this I am splitting the data and applying the operations on train same result saving it for test:


### Handle Missing values:

for Handle Missing values we have used mean median and mode concept where its working really fine and when coming to Outliers I applied a Techniques called std and iqr since it really works fine the worst feature converts into proper feature:



![App Screenshot](https://github.com/yashpuraswani/Credit-Card-Fraud-Customer-Detection/blob/main/Images/download%20(1).png)
