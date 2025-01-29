# About
This project implements a machine learning model to predict the age of abalone based on physical measurements from the Abalone dataset.

# Contents
* Data preprocessing and feature selection
* Implementation of k-Nearest Neighbors (kNN) regression
* Model evaluation and performance analysis

#Process Overview:
_Cleaning:_
Cleaned the dataset by handling missing values and encoding categorical variables. Feature scaling was applied to standardize features like length, diameter, height, and rings.

_Exploratory Data Analysis (EDA):_
Performed basic statistical analysis (mean, median, standard deviation) to understand the data. Visualized the relationships between features and the target variable (age). Before modeling the predictor,
we draw the scree plot to see which attributes contribute to describing data variation the most. 

_Model Selection:_
Implemented a k-Nearest Neighbors (kNN) regression model to predict the age of abalones based on their physical measurements. Tuned the kNN model to identify the optimal value of k for better prediction accuracy.

_Evaluation:_
Evaluated model performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The model showed good predictive power with relatively low error margins.
Conclusion:

The analysis demonstrated that physical measurements like length, diameter, and height are strongly correlated with age prediction.
The KNN model successfully predicted age with reasonable accuracy, but further model improvements could be explored using more advanced regression techniques.

# Requirements
Python, with `pandas`, `numpy`, `scikit-learn`, `matplotlib`

## Note: 
This project was part of a university exam, so some comments or files may be in Serbian.
