# Breast-Cancer-Classification
Apply machine learning to classify benign or malignant breast cancer tumors 

Data preprocessing notebook includes data cleaning, feature selection and splitting the data into train and test sets. 

Our preprocessing also includes selecting the best features for our model. 

We used 3 different feature selections.  
  
1. First group includes all of the features from the data.
1. Second group includes the top 7 features selected based on the the SelectKBest function.
1. Third group includes the top 7 features selected based on their correlation with each other and the diagnosis.

All test and train datasets are in the ```test_train_data``` folder.
All scaler files are in the ```scaler``` folder

Group 1;
Train data files : ```X_train_scaled.csv```
Test data files : ```X_test_scaled.csv```
Scaler file  ```scaler_allfeatures.sav```

Group 2;
Train data files : ```X_train_scaled_sk.csv```
Test data files : ```X_test_scaled_sk.csv```
Scaler file  ```scaler_selectBestFeatures.sav```

Group 3;
Train data files : ```X_train_scaled_cs.csv```
Test data files : ```X_test_scaled_cs.csv```
Scaler file  ```scaler_correlationFeatures.sav```





