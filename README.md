
# Breast Cancer Detection Prediction using Neural Networks
Welcome to the Breast Cancer Detection Prediction project! This project aims to predict whether a breast tumor is benign or malignant using the power of Neural Networks. Leveraging machine learning, this project strives to enhance the accuracy and accessibility of early detection. The dataset we’re using is the well-known Breast Cancer Wisconsin (Diagnostic) dataset, available from the UCI Machine Learning Repository.

Project Overview
What's the Goal?
The main objective is to classify breast tumors as either benign (non-cancerous) or malignant (cancerous) based on various medical attributes like texture, area, smoothness, and more.

What's Our Approach?
We’ll use a simple yet powerful Neural Network (NN) model to achieve this classification. This NN will take the features of a tumor and provide a prediction of its type.

Workflow - Step by Step
Here’s how we move from raw data to accurate predictions:

Importing the Dependencies: Load all the necessary libraries like TensorFlow, Keras, NumPy, and Pandas for data processing, model building, and evaluation.

Data Collection & Processing: Load the dataset and clean it to ensure it's ready for analysis. We handle missing or inconsistent data as needed.

Separating Features and Target: Split the dataset into features (X) (describing each tumor) and target labels (Y) (whether the tumor is benign or malignant).

Splitting the Data: Divide the dataset into training and testing sets to train the Neural Network and evaluate its performance on unseen data.

Standardizing the Data: Normalize the feature values to ensure consistent and efficient model training, boosting performance.

Building the Neural Network: Define and compile a simple feedforward Neural Network using Keras to classify the tumors based on their features.

Visualizing Accuracy and Loss: During training, track the model’s performance by plotting its accuracy and loss over time.

Making Predictions: After training, use the model.predict() function to output prediction probabilities for each class (benign or malignant), along with the confidence levels.

Building the Predictive System: Create a system that can take new data points and predict whether a tumor is benign or malignant, a prototype for real-world applications.
