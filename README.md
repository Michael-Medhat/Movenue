# Movenue
A machine learning project that aims to predict movies Box Office revenue using movie metadata collected from The Movie Database.
# Introduction
  This project was created using a traditional ML pipeline that contains the following phases:
  - Data gathering.
  - Data preprocessing.
  - Modeling.
  - Evaluation.
# Data gathering
  Data was collected from two different sources:
  - The first source is IMDB datasets where we got data about movie title, crew, actors and release data.
  - The second source is The Movie Database where we used there free API to collect data about movie budget, popularity, production companies ...etc.
# Data preprocessing
  In this phase data was cleaned from any noise, and representations were created for certain categorical columns like actors, crew, MPAA ...etc.
# Modeling
  We used two different machine learning techniques in this project both of them are Decision tree based and belong to the ensemble methods.
  - The first modeling technique was Random Forest(RF) with hyperparameters tuning and cross-validation this gave us an R^2 score of 0.76.
  - The second modeling technique was XGboost with hyperparameters tuning and cross-validation this gave us an R^2 score of 0.67.
# Evaluation
  Different Evaluation Metrics were used including Mean Sqaured Error(MSE), Mean Squared Logarithmic Error(MSLE) and coefficient of determination R^2 of the prediction.
