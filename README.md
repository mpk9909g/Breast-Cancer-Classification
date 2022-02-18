# Breast-Cancer-Classification
This project uses machine learning algorithms to predict the class of a breast tumor based on specific features of breast cells.

Click [here](https://mpk9909g.github.io/Breast-Cancer-Classification/) to go to the github page that hosts this repo and explore the website. This site has a link to our [Prediction site](www.bc-predict.herokuapp.com) where you can predict the tumor type of a group of cells based on their features.

## Notebooks in this Repo
Data preprocessing notebook includes data cleaning, feature selection and splitting the data into train and test sets.

Model comparison notebook evaluates all tuned Models against same test set and does KFold Cross Validation on each model with each feature group.

Notebooks for random forest model, KNN model,Logistic regression model,NN model and SVM model includes model optimization for each ML model used here.

## Selected Feautures
We used 3 different groups as our selected features

First group includes all of the features from the data.
Second group includes the top 7 features selected based on the the SelectKBest function.
Third group includes the top 7 features selected based on their correlation with each other and the diagnosis.
We generated train and test data files and scaler files for all the feature groups.

All test and train datasets are in the test_train_data folder. All scaler files are in the scaler folder

Group 1; Train data files : X_train_scaled.csv Test data files : X_test_scaled.csv Scaler file scaler_allfeatures.sav

Group 2; Train data files : X_train_scaled_sk.csv Test data files : X_test_scaled_sk.csv Scaler file scaler_selectBestFeatures.sav

Group 3; Train data files : X_train_scaled_cs.csv Test data files : X_test_scaled_cs.csv Scaler file scaler_correlationFeatures.sav

## Rational of model optimization
We aimed for high accuracy with the least number of features.

We trained and tested our data with KNN, logistic regression, random forest, SVM and Neural network models.


## Reference:

1. https://www.kaggle.com/frankyd/machine-learning-with-breast-cancer
2. https://www.semanticscholar.org/paper/Multisurface-method-of-pattern-separation-for-to-Wolberg-Mangasarian/50537a16eb18e2bc4971165258cba7a071f38cb7
3. https://slideplayer.com/slide/15247250/
4. https://muditkapoor01.medium.com/classification-of-breast-cancer-82d0058f3d35
5. https://math.bu.edu/DYSYS/chaos-game/node6.html
6. https://www.analyticsvidhya.com/blog/2021/10/a-comprehensive-guide-on-deep-learning-optimizers/
7. https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
8. https://www.kenhub.com/en/library/anatomy/cell-nucleus
9. https://www.thoughtco.com/the-cell-nucleus-373362
10. http://www.captodayonline.com/Archives/feature_stories/1006benignmalignantRED.pdf
11. BioRender.com






