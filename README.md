# Multioutput-Regressor and Binary-Classifier

### **Task 1:**Multi-output regression (Prediction of four columns - col_00, col_01, col_02, col_03)
### **Task 2:**Binary classification using Multi-output regression's output as input features inaddition to already existing features. (status 1, status 3)

#### Steps:
1. Importing packages
2. Reading .csv data files into dataframe
3. EDA
4. Data preprocessing
5. Splitting data into train and validation
6. Model building with 3 fold Cross validation and metrics(MSE , R-squared)
      <br> - Multi output regression using Linear regression
      <br> - SVR with Multi-output regressor as wrapper
      <br> - Decision tree for Multioutput regressor
      <br> - Kneighbors Multioutput regressor (Best performance)
7. Testing Regressor on test.csv
8. Model Building of Binary classifierwith 5-fold stratified cv and metrics (Accuracy, precision,recall, f1score) 
      <br> - xgboost
9. Testing Classifier on test.csv
10. Save the predictions as a csv file
11. Save model as pickle file
