+++
author = "Johnny"
title = "Tor Network Traffic Classification"
date = "2024-03-26"
description = "Building a model to classify Tor network traffic"
tags = [
    "ml",
]
+++

I analyzed data and built a model to classify Tor traffic with using data collected by the Canadian Institute for Cybersecurity.

The process of building the model was initially loading and preprocessing network traffic data, including encoding categorical variables and removing potential sources of data leakage. Subsequently, splitting the dataset into training, validation, and testing sets.

Two models, Logistic Regression and Random Forest, are trained and evaluated. For both models, learning curves are plotted to visualize performance and detect signs of overfitting.

Hyperparameter tuning is performed for the Random Forest model using GridSearchCV to optimize its performance. The best parameters are identified and applied to the model, and validation curves are plotted to assess the impact of varying parameters.

Feature importances are analyzed to uncover the most influential variables in the Random Forest model. Finally, the model's performance is evaluated on the test set, and a confusion matrix is generated to assess its classification accuracy.