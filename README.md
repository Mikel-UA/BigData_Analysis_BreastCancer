# BigData_Analysis_BreastCancerWisconsin_Dataset
Attribute selection and preparation of the "Breast Cancer Wisconsin (Original)" dataset for further analysis. Dataset: https://www.kaggle.com/buddhiniw/breast-cancer-prediction/data

Data analysis project using the "Breast Cancer Wisconsin (Original)" dataset, which was obtained from Kaggle. 
This dataset contains comprehensive information about various physical characteristics observed in cells potentially affected by breast cancer, collected between January 1989 and November 1991 by the University of Wisconsin Hospitals, Madison.

The primary objective of this project was to develop a **classification algorithm** capable of distinguishing between **benign and malignant tumors** in breast cancer cells. With the intention of early cancer detection, I used a **supervised learning approach**. Here's a summary of the project:

## Data Exploration: 
I began by exploring the dataset's structure and its attributes, which describe various physical characteristics of breast cancer cells. I identified data quality issues and addressed missing values.

## Dimensionality Reduction: 
Given the dataset's high dimensionality, I performed **Principal Component Analysis (PCA)** to reduce the number of variables while preserving essential information. This reduction enhanced the efficiency of subsequent modeling.

## Data Visualization: 
I utilized libraries such as **ggplot2, corrplot, and GGally** to create informative visualizations, **revealing patterns and correlations within the data**.

## Machine Learning: 
The project involved employing machine learning techniques, specifically **k-Nearest Neighbors (k-NN) with cross-validation**, to classify breast cancer cases as benign or malignant. I evaluated model performance and analyzed **classification accuracy**.

## Result: 
The analysis resulted in a refined dataset with reduced dimensionality while maintaining over **95% of the original data's variance**. This allowed for effective modeling while mitigating the risk of overfitting. The project provided valuable insights into breast cancer diagnosis and improved classification accuracy.
