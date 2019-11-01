# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Results

Random Forest is better than SVM, even without GridSearchCV.
***

## **SVM**

|                | Before GridSearchCV   | After GridSearchCV  |
| -------------- |:---------------------:| :------------------:|
| Training Score | 0.84550               | 0.88651             |
| Testing Score  | 0.84153               | 0.87929             |

---

## **Random Forest**

|                |  Before GridSearchCV  | After GridSearchCV  |
| -------------- |:---------------------:| :------------------:|
| Training Score | 0.99495               | 1.0                 |
| Testing Score  | 0.87643               | 0.89988             |

---

The least performant tried model was KNN with:
	Training score 0.840
	Testing score: 0.850