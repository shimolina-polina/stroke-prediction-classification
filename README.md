# Stroke Prediction Classification

This project focuses on analyzing data, performing visualization, and training five different machine learning models, including two ensemble models, for the task of stroke prediction classification.

## Table of Contents
- [Introduction](#introduction)
- [Data Analysis](#data-analysis)
- [Data Visualization](#data-visualization)
- [Machine Learning Models](#machine-learning-models)
- [Conclusion](#conclusion)

## Introduction

The objective of this project is to develop machine learning models to predict the presence of stroke based on various input features. The dataset used in this project contains information about individuals, including demographic, medical, and lifestyle factors, to facilitate the prediction task.

## Data Analysis

The dataset was subjected to a comprehensive data analysis process to understand its structure and characteristics. The data was cleaned, preprocessed, and examined for missing values, outliers, and inconsistencies. Feature selection techniques may have been applied to identify the most relevant attributes for the stroke prediction task.

## Data Visualization

Data visualization techniques were utilized to gain insights and visualize patterns within the dataset. Various plots, charts, and graphs were created to visualize the relationships between different features and their impact on stroke prediction. These visualizations aided in understanding the data distribution and identifying potential trends and correlations.

## Machine Learning Models

Five distinct machine learning models were trained to predict the presence of stroke based on the selected features. The models were evaluated using appropriate evaluation metrics to assess their performance. The following provides a summary of the models developed:

|Model|Baseline|Gridsearch|
|-|-|-|
|KNN|Precision: 0.75\ Recall: 0.82\ F1-score: 0.79\ ROC AUC score: 0.8531544653444516 |Precision: 0.77\ Recall: 0.77\ F1-score: 0.77\ ROC AUC score: 0.8481729394579811|
|SVC|Precision: 0.73\ Recall: 0.69\ F1-score: 0.71\ ROC AUC score: 0.783156730530161|Precision: 0.77\ Recall: 0.71\ F1-score: 0.74\ ROC AUC score: 0.8192640298072141|
|Decision tree|||
|Random Forest|||
|Gradient Boosting|||

## Conclusion

In conclusion, this project involved data analysis, visualization, and the development of five machine learning models, including two ensemble models, for stroke prediction classification. The models' performance and insights gained from this project contribute to the identification and prevention of strokes, enabling timely medical interventions and improving patient outcomes. Further research and model optimization can be explored to enhance the accuracy and generalization of the stroke prediction models.
