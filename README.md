Taiwo's Portfolio
Analytics portfolio

# [Project 1: Crime Analysis and Visualization](https://github.com/Taiwooladapo/Crime-Analysis-and-Visualization-in-the-city-of-New-York/tree/main)
This is a project I did in my postgraduate degree to analyze and visualize crime rates in the city of New York in the United States of America.
# WORKFLOW
*Retrieved the crime dataset from JSON file source.
*Explored the dataset using the Python programming language.
*Stored the data in a MongoDB database.
*Built an ETL pipeline using Luigi.
*Saved the pipeline results into a PostgreSQL database.
*Utilized Jupyter Notebook to write queries in PostgreSQL for further visualizations.
*Provided recommendations on reducing the crime rate based on insights derived from the data.
# TOOLS USED
Python, Luigi, MongoDB, PostgreSQL, Jupter Notebook and Docker.
# LIMITATIONS AND SUGGESTIONS FOR FUTURE WORK
One limitation of the project is the absence of machine learning algorithms to address high crime rates in New York City. Implementing such algorithms could be considered for future work to further enhance crime prevention strategies.

## Overview of the stored data in a MongoDB Database ![](/images/Saved%20Data%20to%20the%20MongoDB%20Database%20.png)
## Overview of the saved pipeline results into a PostgreSQL Database  ![](/images/Results%20of%20the%20pipeline%20saved%20into%20PostgreSQL.png)

# [Project 2: Investigation-of-socio-economic-factors-influencing-cancer-mortality-in-the-united-states](https://github.com/Taiwooladapo/Investigation-of-socio-economic-factors-affecting-cancer-mortality-in-the-united-states./tree/main)
This project was conducted during my postgraduate degree to develop a robust multiple linear regression model for predicting county-level cancer-related death rates. By utilizing demographic data and the incidence rate of cancer for each county, various regression models were explored to identify the most suitable one.
# Workflow Process
*Utilized a cancer CSV dataset containing data from over 3000 US counties. 
*Performed exploratory data analysis on the dataset.
*Utilized a correlation matrix to examine the relationship between independent variables.
*Removed outliers to improve prediction accuracy.
*Verified the data against the predictions of the linear regression model.
*Built the models using a stepwise regression approach.
*Identified the second model as the most suitable one, which included an estimation of each predictor variable's coefficient, statistical tests of significance, measures of model fit, and diagnostic plots to evaluate the model's performance and underlying assumptions.
# Tools Used
Jupyter Notebook and R programming language.

# [Project 3: Utilizing-different-machine-learning-algorithms-to-detect-credit-card-fraud](https://github.com/Taiwooladapo/Utilizing-different-machine-learning-algorithms-to-detect-credit-card-fraud/tree/main)
During my postgraduate degree, I conducted a project focused on detecting credit card fraud using various machine learning algorithms. The project involved applying five different algorithms to three datasets and evaluating their performance using five evaluation metrics. The datasets were obtained from Kaggle and UCI. The primary objective of the project was to identify the most suitable algorithm that could accurately detect unauthorized credit card transactions with a high level of precision and recall.
# WORKFLOW
*Retrieved the credit card dataset from Kaggle in CSV format.
*Explored and analyzed the dataset using Python programming language.
*Conducted data preprocessing tasks, including data cleaning, handling missing values, and removing outliers.
*Split the data into training and testing sets with a 30:70 ratio.
*Selected classification algorithms, namely Decision Tree, Random Forest, Logistic Regression, Naive Bayes, and Support Vector Machine.
*Trained the models on the training data.
*Evaluated the models using five performance metrics: Precision, Accuracy, F1-score, Recall, and Confusion Matrix.
*Tested the models to assess their performance.
# TOOLS USED
Python and Jupyter Notebook.
# RESULT OUTPUT
The results of the project indicated that the F1-score was the most effective metric, striking a balance between precision and recall. The Random Forest algorithm emerged as the top-performing model, demonstrating high accuracy, precision, recall, and F1-score. This means that it effectively identified fraudulent transactions while minimizing both false positives and false negatives.
# LIMITATIONS AND SUGGESTION FOR FUTURE WORK
The project's limitations include the size and diversity of the dataset. Given more time, it would have been beneficial to employ larger and more diverse datasets to enhance the models' robustness. Furthermore, further investigation could have been conducted to determine the most important features contributing to credit card fraud detection and to enhance the interpretability of the models.

