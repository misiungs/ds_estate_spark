# Apache Spark: estate value regression

<img src="https://github.com/misiungs/readme_images/blob/master/spark_logo.png?raw=true" alt="drawing" width="500"/>

# Problem

The main idea of this project is to explore capabilities of Apache Spark.
For this purpose a dataset from [UCI repository](https://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set) is utilized.
The dataset consists of estate valuation data from one of Taiwan's districts.
It has been used in the paper: Yeh, I. C., & Hsu, T. K. (2018). Building real estate valuation models with comparative approach through case-based reasoning. Applied Soft Computing, 65, 260-271.

# Approach
The provided notebook has been runned on Databricks.
Data exploration is performed with use of both RDDs and DataFrames.
After the initial data analysis two regression models have been utilizied.
First simple linear regression is done.
Next it is followed by Random Forest Regression model.
In both cases hyperparameters tunning with grid search and 5 fold cross validation has been done.

# Conclusions
Different Apache Spark modules have been utilized for purpose of this notebook.
Regarding ML modeling, better results have been achieved for Random Forest approach due to data nonlinearity.