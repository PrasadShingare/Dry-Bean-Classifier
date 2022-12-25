![Python](https://img.shields.io/badge/Python-v.3.10.7-blue.svg)
![Mechine Learning](https://img.shields.io/badge/Machine-Learning-red.svg) 
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-v.1.1.2-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-v.1.5.0-brightgreen.svg)
![NumPy](https://img.shields.io/badge/NumPy-v.1.23.3-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-v.3.6.2-red.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-v.0.12.1-yellow.svg)
![Supervised](https://img.shields.io/badge/Type-Supervised-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-yellowgreen.svg)

![image](https://user-images.githubusercontent.com/88978849/209463790-aabfa5a1-83c7-4e86-976d-64824c41de04.png)


# Dry Beans Dataset

In this project different machine learning algorithms were used to classify the most well-known 7 types of beans in Turkey; Barbunya, Bombay, Cali, Dermason, Horoz, Seker and Sira, depending **ONLY** on dimension and shape features of bean varieties with no external discriminatory features.
- This code was part of a Kaggle competition and came in the 9th place out of 81 teams.

MLP, Xgboost, Catboost and LightGBM classifiers were trained and a final VotingClassifier is used resulting F1-score 0.956 on the training data, 0.935 on validation set and 0.938 on the final testing set.  


## Introduction
The dataset provided in this project is obtained from [UC-Irvine Machine Learning Repository - Dry Bean Dataset.](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)
- **Note**: The data is already splitted with 80% - 20% ratio to training and testing sets respectively, so a part of the data is already separated for final testing and will use the training set for train and validation.


## Purpose
The purpose of this project was to gain introductory exposure to Machine Learning Classification concepts along with data visualization. 
The project makes heavy use of Scikit-Learn, Pandas and Data Visualization Libraries.

## Setup
To run this project, install:\
1- numpy library\
2- matplotlib library\
3- pandas library\
4- seaborn library\
5- sklearn library\
6- scipy library\
