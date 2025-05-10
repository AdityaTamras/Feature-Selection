# Feature Selection on Financial Dataset

Convolve 2.0 PS - 

The necessity for feature selection in banking arises from the scale of data, aiming to enhance the efficiency and effectiveness of machine learning models in this complex and data-rich environment. The given dataset consists of target variable 'y' and 40 features, out of which 20 are original, while the rest are randomly generated variables.

The given project extracts the 20 best features by : 

1. Handling inconsistencies in the data by resampling using SMOTE (Synthetic Minority Oversampling Technique)

2. Obtain best features using the SelectKBest feature selection method

3. Optimize the performance by training the data using an ensemble of AdaBoost, XGBoost and Random Forest Classifiers and calculating feature importance.

This provides an overall accuracy of 95% in predicting the best features.

