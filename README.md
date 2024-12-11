This repository contains the code and resources used for the project "Malaria Forecasting and Image-Based Detection Using Deep Learning Techniques". The project integrates machine learning models to forecast malaria cases and uses convolutional neural networks (CNNs) for detecting parasitized and uninfected red blood cells from microscopic images.

Malaria is a critical global health challenge. This project addresses two main objectives:

Forecasting malaria cases using regression models.
Detecting malaria parasites in blood smear images using deep learning.
The project employs various CNN architectures, including Custom CNN, VGG16, InceptionV3, Xception, and DenseNet, to evaluate their performance on the kaggle malaria dataset.

Data Preprocessing: Cleaning and preparing reported cases and image datasets.
Exploratory Data Analysis (EDA): Trends, regional analysis, and clustering insights.
Forecasting Models: Polynomial and exponential regression for predicting malaria trends.
Deep Learning Models: Implementation of multiple CNN architectures for classification.
Evaluation Metrics: Accuracy, loss, and training performance visualization.

Image Dataset
The kaggle Malaria Dataset was sourced from Kaggle. It consists of 27,558 labeled images of parasitized and uninfected red blood cells. (https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria)
Reported Cases Dataset
Annual malaria case reports categorized by country and region, formatted as a CSV file, were used for forecasting and EDA.


