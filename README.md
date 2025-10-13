# Customer Churn Prediction

**Project Overview**

Customer retention is a critical driver of sustainable growth in today’s competitive market. This project focuses on building a predictive machine learning model to identify customers who are at risk of churning—i.e., discontinuing their use of our service. By accurately predicting churn, businesses can proactively engage high-risk customers with tailored retention strategies, thereby minimizing revenue loss and maximizing customer lifetime value.

***

## Problem Statement

Develop a robust machine learning solution that predicts customer churn based on historical usage behavior, demographic details, and subscription information. The aim is to enable data-driven, personalized interventions, optimize retention strategies, and enhance overall customer satisfaction.

***

## Dataset Description

The dataset contains the following columns:
- **CustomerID**: Unique customer identifier  
- **Name**: Customer name  
- **Age**: Age of the customer  
- **Gender**: Gender (Male/Female)  
- **Location**: City (Houston, Los Angeles, Miami, Chicago, New York)  
- **Subscription_Length_Months**: Months subscribed  
- **Monthly_Bill**: Monthly bill amount  
- **Total_Usage_GB**: Total data usage in gigabytes  
- **Churn**: Binary label (1 = churned, 0 = retained)

***

## Technology Stack

- **Python**: Core language for data engineering and modeling
- **Pandas, NumPy**: Data manipulation and numerical operations
- **Matplotlib, Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive code and analysis
- **Scikit-Learn**: Main ML toolkit (classification, model selection, metrics)
- **Random Forest, Logistic Regression, Decision Tree, KNN, SVM, Naive Bayes, AdaBoost, Gradient Boosting, XGBoost**: Classification algorithms
- **TensorFlow & Keras**: Deep learning models and training utilities

***

## Techniques & Methodologies

- **Feature Engineering**: Standard scaling, VIF for multicollinearity, PCA for dimensionality reduction
- **Model Selection & Tuning**: GridSearchCV for hyperparameter optimization, cross-validation for generalization
- **Model Evaluation**: Accuracy, precision, recall, F1-score, confusion matrix, ROC curve, AUC
- **Outlier & Imbalance Handling**: Outlier detection and class balancing techniques to improve model robustness
- **Regularization & Early Stopping**: Preventing overfitting, ensuring optimal model performance
- **ModelCheckpoint**: Saving and restoring the best performing model during training

***

## Project Outcome

The developed machine learning model predicts customer churn using demographic and usage features. Key benefits and outcomes include:

- **Proactive Retention**: Identify at-risk customers for timely intervention
- **Optimized Resource Allocation**: Focus retention efforts where they will have the greatest impact
- **Business Value**: Reduce churn rates, enhance customer experience, and support growth through improved customer retention strategies

***

**Success is measured by the model’s predictive performance and its effectiveness in supporting business retention initiatives.**
