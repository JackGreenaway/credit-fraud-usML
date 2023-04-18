# Credit Card Fraud Detection with Unsupervised Learning (Encoder)
This repository contains an unsupervised learning algorithm, specifically an encoder, for predicting credit card fraud. The algorithm uses unsupervised learning techniques to automatically detect anomalous or fraudulent transactions in credit card data.

## Dataset
Due to Large File Storage (LFS) constraints, the dataset used for training and testing the algorithm has not been uploaded to this repository. However, the algorithm is designed to work with credit card transaction data that typically includes features such as transaction amount, transaction time, merchant information, and customer details.

The dataset used to train the model can be downloaded from: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Model Overview
The algorithm utilizes an encoder, which is a type of unsupervised learning model, to learn the underlying patterns and structures in the credit card transaction data. The encoder is trained on a labeled dataset of normal transactions, with the assumption that most of the transactions are normal and the fraudulent transactions are rare anomalies. Once trained, the encoder can be used to predict whether a given transaction is normal or fraudulent based on its learned representation of the data.

## Usage
To use this unsupervised learning algorithm for credit card fraud detection, follow the steps below:

- Data Preparation: Prepare your credit card transaction data, making sure it contains the necessary features required for training the encoder.

- Model Training: Train the encoder using the prepared credit card transaction data. The model code and instructions for training will be provided in this repository.

- Model Evaluation: Evaluate the trained encoder using appropriate metrics such as precision, recall, F1 score, or area under the Receiver Operating Characteristic (ROC) curve to assess its performance in detecting credit card fraud.

- Prediction: Once the encoder is trained and evaluated, you can use it to predict whether new, unseen transactions are normal or fraudulent by passing them through the encoder and analyzing the output.