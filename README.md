# Decision Tree Algorithm Project
Introduction
This project is an implementation of a decision tree algorithm to classify individuals based on their demographic variables and income. The dataset used in this project is obtained from the Census Bureau and contains 48,842 instances with seven demographic variables and two target classes: '>50K' and '<=50K'.

## Data Source and Contents
The dataset used in this project is available in the following path: "https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true". The data contains seven columns and 48,842 rows, with a binary target variable indicating whether the individual's income is greater than 50K or not.

## Data Quality Analysis
The first step in the project was to perform a data quality analysis to find missing values, outliers, and NaNs in the dataset. Descriptive statistics of each column were also calculated, and a data quality report was created. Necessary data cleansing and transformation was then performed based on the observations from the data quality analysis.

## Decision Tree Classifier Models
A decision tree classifier model was built using the scikit-learn library. The decision tree produces a sequence of rules that can be used to classify the data. The advantages of using a decision tree include simplicity, ease of visualization, and the ability to handle both numerical and categorical data. The disadvantages of using a decision tree include the potential for complex trees that do not generalize well and instability due to small variations in the data.

## Evaluate Decision Tree Performance
The performance of the decision tree was evaluated by calculating a confusion matrix and the accuracy, precision, recall, and F1 score.

## Tune Decision Tree Performance
Hyperparameter tuning was performed on the decision tree to optimize its performance. Four hyperparameters were varied, including the split criteria, maximum features, minimum sample leaf, and maximum depth, and the performance of the decision tree was recorded for each set of hyperparameters. The best-performing hyperparameter combination was determined based on accuracy.

## Visualize Your Best Decision Tree using GraphViz
The best-performing decision tree was visualized using the GraphViz package.

## Conclusion
Based on the hyperparameter tuning effort, the best-performing decision tree was found, and predictions were made on a new individual's income category using the trained model.

## Deliverables
The project deliverables include a fully functional Jupyter Notebook, the data used in the project, and a README file explaining the project. The Jupyter Notebook contains code for the data quality analysis, decision tree classification, hyperparameter tuning, and visualization of the best decision tree. The README file provides an overview of the project, including the data source, data quality analysis, decision tree classifier models, evaluation of decision tree performance, tuning of decision tree performance, and visualization of the best decision tree.
