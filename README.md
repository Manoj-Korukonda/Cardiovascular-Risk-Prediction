# Cardiovascular-Risk-Prediction

The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,240 records and 15 attributes.

Objective: To build a classification model that predicts Ten Year Coronary Heart Disease in a subject.

I have performed the following steps:

1. Read the file and displayed its columns.

2. Handled missing values, Outliers and Duplicate Data.

3. Calculated basic statistics of the data (count, mean, std, etc), did exploratory analysis and described my observations.

4. Resampled the imbalanced dataset by using Synthetic minority approach

5. Selected columns that will probably be important to predict heart disease.

6. Created training and testing sets (using 60% of the data for the training and reminder for testing) and scaled the data using MinMaxScaler.

7.Built 5 different machine learning models to predict TenYearCHD:

Logistic Regression - 65% Accuracy, 65% Recall

kNN Classification - 93% Accuracy, 92% Recall

Random Forest Classification - 94% Accuracy, 93% Recall

Decision Tree Classification - 91% Accuracy, 90% Recall

Gradient Boosting Classification - 72% Accuracy, 72% recall

Hyperparameter tuned the RandomForestClassification - 98% 

Evaluated each model (f1 score, Accuracy, Precision ,Recall and Confusion Matrix) and plotted a graph for the false positive rate and true positive rate for each model.

