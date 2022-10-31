# Credit Score classification using k-nearest neighbors
Application of K nearest neighbor algorithm to predict credit score

The k-nearest neighbor's algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. While it can be used for either regression or classification problems, it is typically used as a classification algorithm, working off the assumption that similar points can be found near one another. 

This project aims to predict the credit score (Good, Standard, Poor) of a person by training a KNN model using features like annual income, number of bank accounts, number of loans, amount invested monthly, and payment behavior. In total 18 features were used to train a KNN model. The dataset used in this project can be found in this link [Kagle](https://www.kaggle.com/datasets/clkmuhammed/creditscoreclassification). For convenience this dataset was loaded directly in colab using Kaggle API, so to be able to run this colab a Kaggle account is needed. More info in this link [Kaggle API](https://www.kaggle.com/docs/api)

The performance of the model was done by evaluating: accuracy (**0.85%**), F1-score (**0.69%**), and confusion matrix.

![image](https://user-images.githubusercontent.com/94936606/199116976-48680f59-96a6-4b2b-802d-e8b9ab281d84.png)






