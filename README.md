# BigData_Analysis_BreastCancerWisconsin_Dataset
Attribute selection and preparation of the "Breast Cancer Wisconsin (Original)" dataset for further analysis. Dataset: https://www.kaggle.com/buddhiniw/breast-cancer-prediction/data

Data analysis project using the "Breast Cancer Wisconsin (Original)" dataset, which was obtained from Kaggle. 
This dataset contains comprehensive information about various physical characteristics observed in cells potentially affected by breast cancer, collected between January 1989 and November 1991 by the University of Wisconsin Hospitals, Madison.

The primary objective of this project was to develop a **classification algorithm** capable of distinguishing between **benign and malignant tumors** in breast cancer cells. With the intention of early cancer detection, I used a **supervised learning approach**. Here's a summary of the project:

## Data Selection and Preparation:
Selected the "Breast Cancer Wisconsin (Original)" dataset, which consists of 69 features describing cell nuclei attributes.
The data was preprocessed by removing columns with missing values and unwanted identifiers.
Kept the data unnormalized, as normalizing it could result in information loss, given that the values were collected with precision.

## Exploratory Data Analysis (EDA):

Visualized data distributions, showing the proportion of malignant (M) and benign (B) tumors.
Conducted a detailed analysis of attribute correlations using correlation matrices and plots.

## Principal Component Analysis (PCA):

Applied PCA to reduce the dimensionality of the dataset, taking into account the high correlations among some attributes.
Identified and removed highly correlated attributes, optimizing the PCA for feature selection.
Visualized the proportion of variance explained by each principal component.

## Visualization:

Created scatter plots showing the distribution of data points based on the first two principal components.
Demonstrated that the PCA components improved the separation between malignant and benign tumor cases.
