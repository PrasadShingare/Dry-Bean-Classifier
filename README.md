![Python](https://img.shields.io/badge/Python-v.3.10.7-blue.svg)
![Mechine Learning](https://img.shields.io/badge/Machine-Learning-red.svg) 
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-v.1.1.2-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-v.1.5.0-brightgreen.svg)
![NumPy](https://img.shields.io/badge/NumPy-v.1.23.3-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-v.3.6.2-red.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-v.0.12.1-yellow.svg)
![Supervised](https://img.shields.io/badge/Type-Supervised-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-yellowgreen.svg)

# Dry Beans Dataset

In this project different machine learning algorithms were used to classify the most well-known 7 types of beans in Turkey; Barbunya, Bombay, Cali, Dermason, Horoz, Seker and Sira, depending **ONLY** on dimension and shape features of bean varieties with no external discriminatory features.
- This code was part of a Kaggle competition and came in the 9th place out of 81 teams.

MLP, Xgboost, Catboost and LightGBM classifiers were trained and a final VotingClassifier is used resulting F1-score 0.956 on the training data, 0.935 on validation set and 0.938 on the final testing set.  


## Introduction
The dataset provided in this project is obtained from [UC-Irvine Machine Learning Repository - Dry Bean Dataset.](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)
- **Note**: The data is already splitted with 80% - 20% ratio to training and testing sets respectively, so a part of the data is already separated for final testing and will use the training set for train and validation.

Data columns (total 17 columns):

 id   Column           Non-Null Count  Dtype  
 
 0   Area             10834 non-null  int64
 
 1   Perimeter        10834 non-null  float64
 2   MajorAxisLength  10834 non-null  float64
 3   MinorAxisLength  10834 non-null  float64
 4   AspectRation     10834 non-null  float64
 5   Eccentricity     10834 non-null  float64
 6   ConvexArea       10834 non-null  int64  
 7   EquivDiameter    10834 non-null  float64
 8   Extent           10834 non-null  float64
 9   Solidity         10834 non-null  float64
 10  roundness        10834 non-null  float64
 11  Compactness      10834 non-null  float64
 12  ShapeFactor1     10834 non-null  float64
 13  ShapeFactor2     10834 non-null  float64
 14  ShapeFactor3     10834 non-null  float64
 15  ShapeFactor4     10834 non-null  float64
 16  y                10834 non-null  object 
dtypes: float64(14), int64(2), object(1)

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
