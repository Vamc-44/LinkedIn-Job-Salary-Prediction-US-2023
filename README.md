# LinkedIn Job Salary Prediction US 2023
# Dataset Source
https://www.kaggle.com/datasets/arshkon/linkedin-job-postings

# ABSTRACT
In today's dynamic job market, understanding the factors influencing salary levels is crucial for both job seekers and employers. It is imperative to comprehend the factors that impact salary levels in the current dynamic job market. The goal of this project is to create a predictive model for salary estimation based on various job listing features by utilizing LinkedIn job posting data from Kaggle.

The dataset contains details on the company size, location, industry, job title, and necessary skills. Preprocessing the data, exploratory data analysis, and feature engineering are all part of the analysis. A variety of machine learning techniques are used to create a precise salary prediction model. With the help of the project, employers and job seekers will be able to make more informed career decisions and companies will be able to compare their salary offers to industry norms. The outcome makes the labor market more open and effective.

This project is important because it provides employers and job seekers with insightful information. Job seekers who comprehend how education, experience, and skills affect salary expectations will be able to make well-informed decisions about their careers. Employers can use data-driven decision-making to attract top talent by using the model to benchmark their salary offerings. The study's findings bridge the information gap between employers and job seekers for a more open and effective labor market by advancing our understanding of salary determinants and offering stakeholders a useful tool.

# INTRODUCTION
This project explores a wide range of machine learning models and techniques in the quickly changing field of data science to tackle the challenges associated with predictive modeling. The main goal is to use a variety of algorithms, each well-known for its special abilities, to examine and draw conclusions from our dataset about significant patterns.

The project uses a variety of models, such as Linear Regression, KNearestNeighbour, Random Forest, Support Vector Machine with linear and nonlinear kernel, an ensemble model that combines the top three performers, XGBoost, Extreme Learning Machine (ELM), and a simple deep learning model. Every model is chosen according to its unique set of skills, including handling missing data, resistance to outliers, and ability to capture intricate relationships in the data.

The report explores the benefits, capabilities, and visuals linked to each model, providing a comprehensive grasp of their suitability for various kinds of data. Our goal is to gain an understanding of feature importance, decision boundaries, and the cooperative contributions of ensemble models by carefully examining and interpreting visualizations. 

As we proceed through the various stages of the project, which include feature selection, hyperparameter tuning, data preprocessing, and model evaluation, our goal is to deliver not only a predictive solution but also a detailed investigation of the underlying mechanisms driving model performances. We hope to have completed the project with a thorough assessment of each model's effectiveness, establishing the foundation for well-informed predictive analytics decision-making.

This project sets out to investigate a wide range of feature selection strategies, from sophisticated wrapper and embedded techniques to more conventional filter methods. The goal is to deliberately select a subset of features that will both improve the predictive accuracy of the models and reveal the underlying patterns hidden in the dataset.

# Pre-processing 
### Data Collection
### Data Cleaning
### Data Integration
### Data Reduction
### Exploratory Data Analysis

# Models used
-	Linear Regression
-	KNNRegressor
-	RandomForestRegressor
-	Linear SVM
-	Nonlinear SVM
-	Gradient Boosting
- Extreme Gradient Boosting (XGB)
- Extreme Machine Learning Model (ELM)
- Deep Learning Model
- Ensemble model with top 3 models overall

# HYPERPARAMETER TUNING
Hyperparameter tuning is an important phase in the building of a machine-learning model. A model's performance can only be maximized by carefully selecting the ideal set of hyperparameters. Hyperparameters are external configurations that are predetermined and do not change as a result of data-driven learning. Two examples are the learning rate in gradient boosting and the regularization term in linear regression.

We used a reliable method for hyperparameter tuning called GridSearchCV to optimize our salary prediction model. With the help of GridSeacrhCV, we create a parameter range and explore better parameters in the given range to get the best performance of the model. To find the combination that maximizes model performance, this method entails methodically searching across predefined hyperparameter values in the parameter space in an exhaustive manner.

We intend to ensure that our model is optimized, widely applicable, and able to deliver optimal outcomes in real-world scenarios by employing GridSearchCV. This methodological choice demonstrates our commitment to painstakingly optimizing the model for the intended use.
We found the ideal set of hyperparameters that greatly enhanced the performance of our salary prediction model after a thorough hyperparameter tuning process with GridSearchCV. The metrics acquired with these optimally calibrated parameters highlight the improved precision and dependability of our model. Evaluated the best model using Mean Squared Error (MSE) and R^2 score.


