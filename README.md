# Prediction-of-Seagrass-Coverage
This is a seaweed bed coverage prediction using lightGBM

# simplified explanation
Step 1:
For data preprocessing, we use the Pandas library to read in the training and test CSV files. As part of data preprocessing, we remove specific columns, handle missing values, and convert date columns.

Step 2:
We use LightGBM, a gradient boosting framework based on random forest, on the training data. This model is trained to predict seaweed coverage using selected features.

Step 3:
Finally, we create predictions for the test data and save the results to a CSV file. We also use the Matplotlib library to create a graph comparing the predicted results for the training and test data.
