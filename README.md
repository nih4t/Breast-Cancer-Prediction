# Breast Cancer Prediction with Machine Learning

![Breast Cancer](https://github.com/nih4t/Breast-Cancer-Prediction/assets/82613166/4145eeeb-5f8b-4b7a-be91-fae5bc98cc6b)

## Overview

This project focuses on breast cancer prediction using machine learning. The dataset contains several features related to cell characteristics, and the goal is to accurately classify breast tumors as benign (Class 2) or malignant (Class 4) based on these features.

## Dataset

The dataset includes the following independent variables (features) and the dependent variable (target):

- Sample code number
- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Marginal Adhesion
- Single Epithelial Cell Size
- Bare Nuclei
- Bland Chromatin
- Normal Nucleoli
- Mitoses

The target variable is `Class`, where the value 2 represents a benign tumor and the value 4 represents a malignant tumor.

## Project Goal

The main objective of this project is to build a machine learning model that accurately predicts whether a breast tumor is benign or malignant based on the provided features. We have explored and implemented several classification algorithms and evaluated their performance.

## Models Used

The following machine learning models were implemented and compared for breast cancer prediction:

1. Decision Tree Classification
2. K-Nearest Neighbors (K-NN)
3. Kernel SVM
4. Logistic Regression
5. Naive Bayes
6. Random Forest Classification
7. Support Vector Machine (SVM)

## Results

After training and evaluating the models on the breast cancer dataset, the best-performing model was found to be the **Decision Tree Classification** model with an accuracy rate of **97%**. The other models achieved accuracy rates around 95%. The decision tree model demonstrated the highest predictive power for this specific dataset.

