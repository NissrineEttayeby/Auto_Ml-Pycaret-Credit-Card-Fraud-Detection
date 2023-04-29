![image](https://user-images.githubusercontent.com/108592629/234149627-201787e1-fed1-4466-907a-0911608576ab.png)


PyCaret is a workflow automation tool for supervised and unsupervised machine learning. It is organized into six modules and each module has a set of functions available to perform some specific action.Each function takes an input and returns an output, which in most cases is a trained machine learning model. Modules available as of the second release are:

Classification
Regression
Clustering
Anomaly Detection
Natural Language Processing
Association Rule Mining



# Installing PyCaret

Installing PyCaret is simple through pip and it takes only a few minutes. PyCaret's default installation only installs hard dependencies as listed in the requirements.txt file on the repo.

``pip install pycaret``

#### To install the full version:

``pip install pycaret[full]``

### Features

PyCaret is loaded with functionalities. You can go from processing your data to training models, and then deploying them on the cloud within a few lines of code.It has over 70 untrained models for supervised and unsupervised tasks :
![image](https://user-images.githubusercontent.com/108592629/234149701-e01b7bb6-5f5b-4d2b-931f-f391f0dffbfb.png)



# Project : Credit card fraud detection


## Context 
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase

## Content

The dataset contains transactions made by credit cards.It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features "V1, V2, … V28" are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise..

## Comparaison between models using pycaret
![image](https://user-images.githubusercontent.com/108592629/234154939-41a0168d-da1b-40ce-86d2-b217d82ba22a.png)
