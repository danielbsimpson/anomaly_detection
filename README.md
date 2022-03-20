# Anomaly Detection using Machine Learning

This project was designed to experiment with various machine learning applications for anomaly detection. The projects is made up of 3 parts:
* 1. Unsupervised Techniques
* 2. Unsupervised models on labeled credit card data
* 3. Supervised models on the labeled credit card data.

The first part of the project explores Unsupervised Techniques on various anomaly data sets available online.

![](/Images/Unsupervised_Design1.JPG)

![](/Images/Project_Design.JPG)

## Unsupervised Techniques
For this part of the project 4 datasets from the NAB (Numenta Anomaly Benchmark) were used to experiement with the unsupervised machine learning algorithms
The algorithms tested are:
* k-means
  * centroid measurement for anomaly detection
  * Gaussian Distribution for anomaly detection
* Isolation Forest
* SVM
* LSTM Neural Networks

An outlier fraction of 0.001 is used throughout and the algorithms are compared with each other across each dataset.

## Unsupervised models on labeled credit card data
For this part of the project a dataset of credit card transactions with known fraud cases labeled is used. The data contains amount of the purchase, along with 28 additional normalized features. The previous algorithms are then applied to the data, to identify which algorithm might be the most useful in the early stages of fraud detection.

## Supervised models on the labeled credit card data
In the final part of this project the following models were used for training/testing:
* Logistic Regression
* K-nearest neighbor
* Supprt Vector Machine
* Decision Tree
* Neural Network
* XGBoost

The models are accessed using accuracy, precision, recall and F1 score. The best model was then selected for Hyperparameter tuning using a grid search algorithm. The tuning was conducted twice, once optimizing for the Precision score, and a second time optimizing for the F1 score.

The conclusion of the project provides an overview of which models should be used when no labeled data is available, when only a limited amount of data is available, and when a substantial amount of labeled data is collected.

Please see the Jupyter Notebooks for further information.
