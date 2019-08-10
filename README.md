# Project: Analyze Churn Rates using PySpark

![Build Status](https://s16353.pcdn.co/wp-content/uploads/2018/06/Churn.png)

## Project Motivation
This is the project we have an example of a virtual company called 'Sparkify' who offers paid and free listening service, the customers can switch between either service, and they can cancel their subscription at any time.We will use spark to analyze user behavior data from music app Sparkify.The dataset contains two months of sparkify user behavior log. The log contains some basic information about the user as well as information about a single action. A user can contain many entries. In the data, a part of the user is churned, through the cancellation of the account behavior can be distinguished.

You can read a blog version of this analysis on my [Medium blog](https://medium.com/p/f3e1ece47b2e/).

## Dataset
 The given customers dataset is huge (12GB), thus the standard tools for analysis and machine learning will not be useful here as it will not fit in the computer's memory (even the data can fit in the memory of a 32GB computer, the analysis, and computations require way more than that amount, and the analysis will crash the system). The safe way to perform such analysis is to do it using Big Data tools like Apache Spark which is one of the fastest big data tools. For this project we will be analyzing a smaller subset of the data of 128 MB consisting of 286,000 records of user data.

## Installation

The following resources need to installed:

- Python 3.6.x (The programing language)
- pySpark 2.4.x (Machine learning library for big data)
- matplotlib 3.03 (A plotting library)
- pandas 0.23 (numerical calculations library)
- jupyter (The programming notebook interface)

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. And for Spark, you can do this using AWS or IBM Cloud.

## File Descriptions:
| File | Description |
| ------ | ------ |
| Sprakify.ipynb | Main file of the project, it demonstrates the process of using pyspark to explore the data and build the model.
|Sprakify.html | The HTML version of the code in the .ipynb Jupyter notebook|



## Resources

- [Spark Pipelines](https://towardsdatascience.com/feature-encoding-with-spark-2-3-0-part-1-9ede45562740)
- [Classificaiton problem](https://towardsdatascience.com/machine-learning-with-pyspark-and-mllib-solving-a-binary-classification-problem-96396065d2aa)
- [VectorIndex](https://spark.apache.org/docs/latest/ml-features.html#stringindexer)
- [Sklearn GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
- [Sklearn Classification Report](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html)
