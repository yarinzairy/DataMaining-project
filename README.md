Predicting Young Football Players' Potential Using FIFA Data


This project explores the prediction of young football players' potential using data from the FIFA 22 video game. The goal is to build a more objective model that avoids the possible biases in the game's own player ratings and instead provides a data-driven alternative based on individual performance attributes.


Project Summary
We analyzed the FIFA 22 dataset to evaluate and predict the potential of players under the age of 23. Our approach included:

Preprocessing the dataset to remove irrelevant or redundant information.

Creating a custom weighted overall score based on role-specific attributes.

Applying a linear regression model to predict a player's potential rating.

Building a "Future Super Team" composed of the top predicted young players.


Key Features
Regression model achieves RMSE = 3.79 and R = 0.79

Custom weighted overall scores by position

Analysis reveals discrepancies in FIFA’s rating system, likely due to popularity bias

A recommended 11-player young stars squad built from model predictions


Dataset
Source: Kaggle - FIFA 22 Complete Player Dataset

Includes 19,239 players and 110 attributes (physical, skill, and metadata)


Methods
Data cleaning and transformation

Feature selection and engineering

Linear regression modeling

Exploratory data analysis and visualization (age distributions, correlation matrices, etc.)


Conclusions
Our analysis suggests that FIFA’s in-game player ratings may not always reflect true performance indicators. By applying data mining techniques and custom weighting, we offer a more analytic and arguably fairer method for assessing young talent.

Future Work
Apply the model on yearly updated datasets to track player development

Integrate time-series or advanced ML models (e.g., random forest, XGBoost)

Explore external real-world performance data for cross-validation


References
Cotta et al. (2016). Using FIFA Soccer Video Game Data for Soccer Analytics

Al-Asadi & Tasdemir (2021). IEEE Access: Empirical Comparisons for Characterizing Football Players

Kaggle Dataset: FIFA 22 Complete Player Dataset
