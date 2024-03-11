# Breast Cancer-Identification-Model
This repository contains a simple breast cancer identification model implemented using Logistic Regression. The model predicts whether a given tumor is malignant or benign based on various features.

##Data Collection and Processing
The breast cancer dataset is loaded from the scikit-learn library. The data is then converted into a pandas DataFrame for easy manipulation. The target column is added to the DataFrame, where 1 represents benign tumors and 0 represents malignant tumors.

##Model Training
The dataset is split into training and testing sets using an 80-20 split ratio. Logistic Regression is employed as it is well-suited for binary classification tasks. The model is trained on the training data.

##Model Evaluation
The accuracy of the model is evaluated using both training and testing data. The accuracy on the training data is approximately 95.16%, while the accuracy on the testing data is approximately 95.61%.

##Building a Predictive System
A predictive system is implemented where you can input the features of a tumor, and the model will predict whether it is malignant or benign. An example input data point is provided as a tuple, and the model predicts the class of the tumor.

##Example
An example input data point is provided below:

input_data = (20.18,23.97,143.7,1245,0.1286,0.3454,0.3754,0.1604,0.2906,0.08142,0.9317,1.885,8.649,116.4,0.01038,0.06835,0.1091,0.02593,0.07895,0.005987,23.37,31.72,170.3,1623,0.1639,0.6164,0.7681,0.2508,0.544,0.09964)

Running this input through the model will output the prediction.

