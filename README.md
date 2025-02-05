   Breast Cancer Prediction using Logistic Regression:


This project uses the famous breast cancer dataset from scikit-learn to predict whether a given breast cancer tumor is malignant or benign. The dataset includes various features like the mean radius, texture, and smoothness of the tumor. The target variable indicates whether the tumor is malignant (0) or benign (1).

Project Overview:

In this project, we are using the Logistic Regression algorithm from scikit-learn to build a binary classifier that can predict whether a breast cancer tumor is malignant or benign based on input features.

Features:

1. Logistic Regression for binary classification
2. Data preprocessing, including handling missing values
3. Model evaluation using accuracy score
4. Predictive system for individual input data

Prerequisites
To run this project, you need to have the following libraries installed:

1. numpy
2. pandas
3. scikit-learn
4. matplotlib (optional for visualization)

Steps:

1. Data Collection & Processing: The dataset is loaded from scikit-learn's built-in datasets. It is then converted into a pandas DataFrame, where the target variable is added as a new column (label).

2. Handling Missing Values: Missing values (if any) in the dataset are handled using imputation or by dropping rows/columns depending on the situation.

3. Splitting Data: The data is split into training and testing sets using an 80-20 split.

4. Training the Logistic Regression Model: The Logistic Regression model is trained using the training set, and the accuracy is evaluated using both the training and testing datasets.

5. Evaluation: The accuracy score of the model is calculated to determine its performance.

6. Prediction: A predictive system is built, allowing the user to input feature values for a single sample and predict whether the cancer is benign or malignant.

Example Output:

Accuracy on training data = 0.98:

Accuracy on test data = 0.96:

Prediction: [1]:

The Breast Cancer is Benign

Model Accuracy

Training Accuracy:-----> 98%

Test Accuracy:-------> 96%

The Logistic Regression model performs well in classifying breast cancer as malignant or benign, with high accuracy on both training and test data. This system can be used for early detection of breast cancer based on the input features.

