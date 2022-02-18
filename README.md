# Breast-Cancer-Classification
This project uses machine learning algorithms to predict the class of a breast tumor based on specific features of breast cells.

To go to the github pages that hosts this repo type www...... into your browser and explore the website. This site has a link to www.bc-predict.herokuapp.com where you can make prediction based on the cell features.

Notebooks in this Repo
Data preprocessing notebook includes data cleaning, feature selection and splitting the data into train and test sets.

Model comparison notebook evaluates all tuned Models against same test set and does KFold Cross Validation on each model with each feature group.

Notebooks for random forest model, KNN model,Logistic regression model,NN model and SVM model includes model optimization for each ML model used here.

Selected Feautures
We used 3 different groups as our selected features

First group includes all of the features from the data.
Second group includes the top 7 features selected based on the the SelectKBest function.
Third group includes the top 7 features selected based on their correlation with each other and the diagnosis.
We generated train and test data files and scaler files for all the feature groups.

All test and train datasets are in the test_train_data folder. All scaler files are in the scaler folder

Group 1; Train data files : X_train_scaled.csv Test data files : X_test_scaled.csv Scaler file scaler_allfeatures.sav

Group 2; Train data files : X_train_scaled_sk.csv Test data files : X_test_scaled_sk.csv Scaler file scaler_selectBestFeatures.sav

Group 3; Train data files : X_train_scaled_cs.csv Test data files : X_test_scaled_cs.csv Scaler file scaler_correlationFeatures.sav

Rational of model optimization
We aimed for high accuracy with the least number of features.

We trained and tested our data with KNN, logistic regression, random.




