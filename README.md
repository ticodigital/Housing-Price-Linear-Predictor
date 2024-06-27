# Housing-Price-Linear-Predictor

## Abstract
This project utilized Python libraries to build a model for predicting residential property values. Leveraging a dataset of 80 features for 100 houses, the goal was to achieve an R-squared score exceeding 80%. The project explored data cleaning, feature engineering (including one-hot encoding for categorical features), and correlation analysis to identify key influencing factors.
Multiple linear regression models were built and compared, with the best model achieving an R-squared score of 96.2%. This champion model incorporated top positive and negative correlations alongside one-hot encoded categorical variables. Notably, including categorical features yielded stronger correlations than solely using numeric variables.
A crucial challenge involved selecting features with no missing values in the test data, as linear regression cannot handle them. This project demonstrates the potential of linear regression for accurate house price prediction, emphasizing the importance of data preparation and feature selection in achieving optimal results.

## Introduction
The Housing Price Linear Predictor project harnesses the power of Python, scikit-learn, pandas, NumPy, matplotlib, and seaborn libraries to estimate residential property values. Leveraging a diverse dataset of 80 characteristics across 100 houses, the model aims for an accuracy exceeding 80% (R-squared > 0.8).

Beyond price prediction, the project identifies vital factors influencing value and explains the model's inner workings.
The journey begins with data exploration in Jupyter Notebook, followed by meticulous cleaning: removing near-constant features, addressing duplicates, and strategically imputing missing values. In feature engineering, the non-numerical features get transformed using one-hot encoding.

Next, the project analyzes the price distribution and identifies potential linear relationships with other variables through scatter plots and correlation analysis.

Finally, multiple linear regression models are built and compared, selecting the champion based on its performance. This champion model will be tested against unseen data to validate its real-world effectiveness.
