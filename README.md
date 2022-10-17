# Cardiovascular-Risk-Prediction
Cardiovasculardiseases (CVDs) are a group of disorders of the heart and blood vessels and include Coronary Heart Disease and other conditions.

The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

* Approach Used:
Firstly, we performed Exploratory Data Analysis on the dataset. We looked for missing values and dropped the rows with the missing values and treated the outliers in our dataset by applying IQR method. We then performed Feature Engineering by adding the relevant columns and doing categorical encoding. Also we dropped few columns which were higher correlated with other columns.

In the dataset, there was a class imbalance which we corrected by using the SMOTE technique and predicted the results based upon it. we applied different machine learning algorithms to train the model and predict 10-year risk of cardiovascular disease. Also, we performed hyperparameter tuning, to find out the best set parameters for the given algorithm. After implementation of various algorithms, we’ve noticed that Gradient Boosting is the stand out performer among all the models with an F1 score of 0.89.





* Conclusion:

  * Gradient boost model is the most accurate model among all the models, on the basis of evaluation parameters such as Accuracy (90%), Precision (89%), Specificity (91%), F1 score (88%), and AUC-ROC score (96%)
  
  * Age is the most important feature according to Gradient boost.
  
  * Logistic Regression model has the least Accuracy (70%).
