# Breast-Cancer-Classification
Apply machine learning to classify benign or malignant breast cancer tumors 

Data preprocessing notebook includes data cleaning, feature selection and splitting the data into train and test sets. 

Our preprocessing also includes selecting the best features for our model. 

We used 2 different feature selections.  
  
1. First group includes all of the features from the data.
1. Second group includes the top 7 features selected based on the correlation heat map and/or the SelectKBest. 

Train and test input data files for group 1  are ```X_train_scaled.csv``` and ```X_test_scaled.csv``` respectively.
Scaler file for group 1 is ```scaler_allfeatures.sav```.

```encoded_y_train.csv``` and ```encoded_y_test.csv``` files have the label encoded outcomes. 

```y_train_categorical.csv``` and ```y_test_categorical.csv``` files have the one hot encoded outcomes. Both type of files were used in this study. 


