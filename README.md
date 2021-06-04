# credit-card
Credit card prediction using gradient boosting algorithm:
1.	The given dataset consist of train and test csv files.
2.	I have load the data using pandas data frame object
3.	After loading the data I have generated statistical and visual report for the given data and I noticed that the target variable is depend highly on vintage value and average balance.
4.	After loading the train and test files I checked for missing values in the data.
5.	I found there is only one column with lots of missing values, hence I cleaned the data by dropping rows which contains missing values
6.	After cleaning the data I converted all the categorical data into numerical data.
7.	After converting into numerical data I have split the data into train and test.
8.	Then I created logistic regression and random forest model but get less accuracy of around 85%, hence I created Gradient boosting model and achieved accuracy of around 92%.
9.	Then I predicted the it on test dataset and created the model.
