# Credit Card Fraud Detection

By [Rifky Aliffa](https://github.com/Penzragon)

![Image](https://eastwestbank.com/ReachFurther/NewsArticleStore/519/Credit-card-fraud-top1.jpg)

## Dataset

The dataset used in this project is a credit card fraud detection dataset. It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are `Time` and `Amount`. Feature `Time` contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature `Amount` is the transaction `Amount`, this feature can be used for example-dependant cost-sensitive learning. Feature `Class` is the response variable and it takes value 1 in case of fraud and 0 otherwise. The dataset is available at [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## Objective

The objective of this project is to build an artificial neural network model which can predict the class of a transaction based on the principal components.
