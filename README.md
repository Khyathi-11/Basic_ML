Approach:

1.Gathering the Data:

Dataset from Kaggle
Consists of two CSV files (one for training and one for testing)
Total of 133 columns - 132 columns represent the symptoms and the last column is the prognosis

2.Cleaning the Data:

All the columns are numerical, the target column i.e. prognosis is a string type and is encoded to numerical form using a label encoder

3.Model Building:

Use this cleaned data to train the Support Vector Classifier, Naive Bayes Classifier, and Random Forest Classifier
We will be using a confusion matrix to determine the quality of the models

4.Inference:

After training the 3 models we will be predicting the disease for the input symptoms by combining the predictions of all 3 models

5.Conclusion:

Define a fn that takes symptoms separated by commas as input, predicts the disease based on the symptoms by using the trained models, and returns the predictions in a JSON format
