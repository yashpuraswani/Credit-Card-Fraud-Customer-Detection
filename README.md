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

### Before Handling Outliers on of the feature looks like this:



![App Screenshot](https://github.com/yashpuraswani/Credit-Card-Fraud-Customer-Detection/blob/main/Images/download%20(2).png)


### After handling Outliers using some IQR Techniques the data comes to position called Normal Distribution:


![App Screenshot](https://github.com/yashpuraswani/Credit-Card-Fraud-Customer-Detection/blob/main/Images/download%20(3).png


If this looks good you can follow the entire concept which mentioned in the above coading file:

Meanwhile while working with feature engineering part I am taking the help of sklearn and fearture engine frameworks for better EDA and model developement part:

Techniques done using sklearn and feature engine :

              - Variable Transformation
              - Outliers
              - data scaling concepts 



## Finally entire data is set ready for Model developement Purpose:
since the data is not balanced using Upsamping and down sampling concepts I Handle them.

Know I selected KNN , naive bayes , Logistic Regression , Decision Tree and Random Forest for Model developement:

since after training the model I got the results of :

                  - KNN Accuracy : 0.7570969469737547
                  - NB Accuracy  : 0.7403856454204606
                  - LR Accuracy  : 0.7867880735582932
                  - DT Accuracy  : 0.7030887341546153
                  - RF Accuracy  : 0.808766291733619

since almost the results are very close to each other I stuck around to select the best model: No worries I am having AUC and ROC concept so I find out FPR and TPR using Grapical represntation and selected best model which is Logistic Regression:


![App Screenshot](
https://github.com/yashpuraswani/Credit-Card-Fraud-Customer-Detection/blob/main/Images/download%20(4).png)



Entire code and hidden information You can get it from the above coding file:



## 🛠 Skills

        1.Python 
        2.Machine learning 
        3.Statistics
        4.Mathematics
        5.Numpy 

    


## Support

For support, email yashpuraswani804@gmail.com .


## Acknowledgements

 - [feature engine](https://feature-engine.trainindata.com/en/latest/)
 - [Sklearn](https://scikit-learn.org/stable/)



