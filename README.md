# ML_Algorithm-Logistic_Regression
This repository will include the use of ML algorithm on predicting the classification dataset. We have used the Logistic regression to build the model
We have the dataset of bank details that contains that target variable as classification data. It contains that data of whether the customer has bought the insurance or not. Actually, this is also called as dependent columns. Whereas there are other columns are somehow related to the result classification data and they are independent columns
I have got the accuracy_score of 94% on this model.
I am sharing all the modules, codes and algorithm I have used to get this model.
# Table Of Content
## Importing Library
I have imported the libraries like numpy and pandas to do the basic data analysis of the given datasets
## Uploading the Dataset
I have uploaded the dataset from the google drive to my colab notebook on which I have built this model.
## Exploratory Data Analysis
I have used the libraries like numpy for numerical operations, pandas for data wrangling activity, seaborn and matplotlib for creating visuals and doing data analysis. These all methods have been basically to understand the dataset. I have removed the duplicates rows, outliers in the same process.
## Data Cleaning
I have used the basic statistic method for the data cleaning.
## Variance Inflation Factor
I have used this technique to remove the unwanted columns that can impact the model accuracy.
## Splitting the Data
After the VIF has been done, I have splitted the data in train and test data. It will include x_train, x_test, y_train, y_test. x_train and y_train has 75% of the data. while x_test and y_test have remaining 25% of the data.
## Building the model
I have imported the logistic regression algorithm from scikit-learn and used it to build the model by using the x_train and y_train data.
## Predicting the model efficiency
I have used x_test, y_test data to predict the accuracy of the model.
