# Introductions

### Part 1. Process train data

- Feature engineering

- Split the feature 'problem hierarchy' into 'Units' and 'Sections'

- Encode categorical features into numeric features

- Build heatmap for finding the correlation of each feature

  

### Part 2. Build model

- Use random forest classifier as ensemble meta-estimator

- Use GridSearchCV to do a exhaustive search over specified parameter values to tune hyperparameters

  

###  Part 3.  Process test data

- Select samples from test.csv that 'Correct First Attempt' value is not NaN

- Split the feature 'problem hierarchy' into 'Units' and 'Sections'

- Encode categorical features into numeric features

  

### Part 4. Apply model on test data and do the prediction



### Part 5. Evaluate the model

- compute RMSE and AUC scores

-  plot Confusion matrix

-  print Classification Report

  

### Part 6. Fill out test.csv 



