# This is jupyter notebook that predicts prices for properties with the following ml algorithms:
- Linear Regression
- Random Forest Regression
- K neighboors
- Ridge Regression
- Lasso
- Bayesian
- Elastic


## Steps Followed
1. Retrieve the datasets from the 'listings' and 'types' APIs and load the data into
separate pandas dataframes.
2. Perform a preliminary exploration of the data.
3. Clean and preprocess the data, as necessary.
4. Join the 'listings' and 'types' dataframes on the type_id foreign key to create a
single, merged dataframe.
5. Keep only properties of types: apartments, marionettes, and detached houses.
6. Select and apply appropriate regression algorithms to predict the sale price per
sqm of properties based on their features and those of their property types.
7. Evaluate the performance of the models and select the best model based on
evaluation metrics.
8. Use the best model to make predictions on a sample of properties and compare
the predictions to their actual sale prices.
