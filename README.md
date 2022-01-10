# Udacity-Arvato-Financial-Services

## Capstone Project: Create a Customer Segmentation Report for Arvato Financial Services
About this project is part of Data Science Nanodegree Program by Udacity. The project aim is to predict individuals who are most likely to become customers for a mail-order sales company in Germany.

## Medium Blog Post
Medium blog post link:
- https://medium.com/@felipehuman/customer-segmentation-report-for-arvato-financial-services-844348a5efa7

## Introduction

In this project, we are provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

We approach this project in two main phases:

- Use Unsupervised Learning to perform customer segmentation and identify clusters/segments from general population who best match mail-order company's customer base.

- Use Supervised Learning to identify targets for marketing campaign of the mail-order company who could possibly become their customers.

## Technical overview

Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Because of the large volume of source data, we build different functions for data preprocessing to get rid of unnecessary and outlier data and implement Dimensionality Reduction and Clustering to identify segments or clusters. Due to the nature of the data there is a large output class imbalance, where most individuals did not respond to the mailout. AUC (Area under the Curve)/ROC(Receiver Operating Characteristic) is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

Following concepts implemented and covered in detail in the notebook:

- Data Exploration & Cleansing
- Dimensionality Reduction
- Clustering
- Supervised Learning
- Final Model Evaluation
- Feature Importance
- Analysis of identified important features in clusters to find relevance
- Kaggle competition

### Main libraries
The Python version that was used for the development of this project was Python3. Here are the main libraries I used in my Jupyter Notebook:

- Numpy
- Pandas
- Sklearn
- Seaborn
- Matplotlib
- Plotly
- Scipy
- Math

## File descriptions - Master Branch
- Arvato Project Workbook.ipynb: This Jupyter Notebook incorporates Data Transformation, Hyperparameter Optimization, Machine Learning Models (Supervised and Unsupervised algorithms), and Visualizations.

- DIAS Attributes.xlsx: Excel spreadsheets listed features with a brief explanation of some variables.

## Licensing, Authors, Acknowledgements
This project was completed as part of the [Udacity Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

The data is provided by Arvato Financial Services, a Bertelsmann subsidiary.It is important to mention that the data used are not open to the public, since for the development of this project it is necessary to agree with the data use policy of the company to make use of this information.

As additional material I used an article published by Palouda entitled: ["Udacity Arvato-Bertelsmann Project"](https://cpalouda.medium.com/udacity-arvato-bertelsmann-project-789d20bf8513), which was of great help for the development of this project. 


