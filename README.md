# Nashville Real Estate Investment Using Logistic Regression, Descision tree, Random Forest & Gradient Boosting Algorithms

The exercise aims to effectively code and build a variety of classification models using logistic regression, decision tree model, random forest model, and gradient boosting model to predict whether properties in the Nashville area are being undervalued or overvalued. Steps include

•	Performing cleaning operations & feature engineering to prepare data for modelling.

•	Use the logistic regression, decision tree, random forest, and gradient boosting algorithms to predict whether properties in the Nashville area are undervalued or overvalued.  

•	Interpret the results and comment on the accuracy of the model and compare all models using different performance metrics.




## Technologies


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) 

<br>

## Data Cleaning & Feature Engineering 


Null Value Check, Outlier Check, and Checking the categorical feature balance/distribution were some of the data cleaning tasks. 

For Exploratory Data Analysis, The features were closely studied and various plots were used to understand how the features were correlated.

## Modelling

Each Model was built after various data preprocessing steps like encoding, scaling, and feature engineering.

Also, Hyperparameter tuning was used to establish an optimal number of nodes, estimators and other parameters for building optimum models.

## Conclusion


|                  |     Logistic model    |     Decision Tree    |     Random Forest    |     Gradient Boosting    |
|------------------|-----------------------|----------------------|----------------------|--------------------------|
|     Accuracy     |     77.7%             |     79.1 %           |     78%              |     79.1%                |
|     Precision    |     0.6038            |     0.7288           |     0.5655           |     0.8743               |
|     Recall       |     0.1529            |     0.176            |     0.283            |     0.1315               |
|     AUC          |     0.561             |     0.5782           |     0.6053           |     0.60056              |


Based on the comparison table comparing important metrics like accuracy, precision, recall and AUC, it can be seen that gradient boosting has the highest accuracy and a better precision rate, indicating the accuracy of positive predictions. Also, the AUC of gradient boosting is the highest which signifies that it is a better classifier overall. Hence, based on these 3 key metrics, the gradient boosting model is recommended.

