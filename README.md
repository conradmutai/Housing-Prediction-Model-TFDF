# Housing Prediction Model (Using TFDF)
## Introduction
This was made for Kaggle Competition: House Prices - Advanced Regression Techniques

This model utilizes a data set with information on the features of the houses and the sale price that is given to each product. 

This repository provides the notebook, with the CSV files provided from the Housing Price Prediction Competition from Kaggle, for which this model received a score of 0.13514 (the closer the score is to 0, the more accurate the model's predictions are). I will continue to use my learning progress to reduce the score further. 

This repository can also be used as a way to track the progression of this model and the development of skills throughout, if curious.

## Scores
* Attempt 1: 0.13514
* Attempt 2: 0.23787
* Attempt 3: 0.15425

## Data Analysis
The notebook contained in this repository also features an extensive exploration of the correlation and functional relationships between the features (**numerical ones only**) and the output value (Sale Price). It also further utilizes a wide range of graphical techniques and methods to provide a visual representation of the relationship between the features and the output value.

## Selecting the Features
The notebook also displays a methodology used to select features, including how numerical features can be chosen by a threshold of the correlation between the features and output value. It also displays which features are missing from data points to be removed from the dataset. These all come together to improve the efficiency, accuracy, and cost of the model, making this model a lot easier to use and predict values through.

## Selecting a Model
The factor of decision making made it relevant to choose regression decision trees as the best way of predicting values, which led to the choice to use `GradientBoostedTreesModel` from TensorFlow to make predictions for the values. The reason is further explored within the notebook, and is coupled with explanations of how this was chosen, why this was chosen, what it does, and the Root-Mean-Squared Error (RMSE) of this model that is produced by it.

## Predictions
The predictions are also displayed at the end of this notebook.

## Goals of this Repository
* Continuously revisit and improve the score of the model
* Use methods I learn across my journey to improve the code
* Use other methods of prediction (Deep Learning Model using Regression)
