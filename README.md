# Credit-Risk-Classification

Overview
Purpose of this study is to create a logistic regression model to predict credit risk for loans. The model has 2 classifications which are healthy loans(0), high risk loans(1). Depending on outcome of accuracy, precision and recall financial institution can use this model to identify clients for the loan lendings.

Steps Involved
1. Created a panda dataframe using credit_risk.csv
2. Created labes(y) and features(X) using the data frame
3. Split the data using train_test_split in scikitleearn library
4. Created a logistic regression modelusing original data
5. Evaluated the models perfofmance using confusion matrix and classification report from scikitlearn library

Results
The precision for healthy loan is 100% which means that every time predicted as healthy loan is correct, where as precision for high risk loan is 85% which means 85%of loans predicted as high risk are actually high risk loans and there is around 15% false positive records.
The recall for healthy loan is 99% which means that model correctly idetifies 99% of healthy loans, on the other hand model identifies 91% high risk loans as actual high risk loans.
Accuracy of the model is 99%.
The precision and recall for high risk loan are lower than healthy loan, which may be due to the data imbalance(Records for healthy loan is 18765 and high irsk loan is just 619)

