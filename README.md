# F1-Racing

DS605: Fundamentals of Machine Learning

A
Project on
F1 Race Prediction using Regressors

Submitted by

Meenakshi Iyer
202418031
Kshiti Mulani
202418034
Sreelakshmi Nair
202418037
Shaili Parikh
202418049

Submitted to

Prof. Arpit Rana

and
Teaching Assistants:

Himanshu Beniwal
Bhavan Bhatt
		













Project Overview:

The main objective of this project is to use regression methods to predict the winner of Formula 1 Grand Prix races in 2024. By analyzing both historical and current data, we aim to provide accurate predictions to help fans, teams, and bettors make informed decisions. Our focus is on identifying the key factors that will influence race outcomes throughout the 2024 season.


Data Analysis & Pre-processing:

We collected data from various sources, including the Ergast Data repository, which offers comprehensive historical Formula One data. This dataset includes race positions, points, grid placements, laps, statuses, and detailed driver and constructor information. Exploratory data analysis was conducted to uncover crucial factors affecting race outcomes, which informed the development of our predictive models.


Machine Learning Models:

We employed multiple regression models to predict the winners of Formula One races in 2024. The models we employed include Decision Tree Regression, Random Forest Regression, and Gradient Boosting Regression. Decision Tree Regression offers simplicity and interpretability, Random Forest Regression handles large, complex datasets effectively, and Gradient Boosting Regression excels in accuracy and modeling intricate data relationships. These models were chosen to provide robust predictions of race outcomes and lap times.


Model Application and Evaluation:

Our models predicted the winners of specific Grand Prix races, and we compared their performance to select the most effective one. For evaluation, we used Root Mean Square Error (RMSE) and Mean Square Error (MSE) to measure prediction accuracy, assessing how closely predictions aligned with actual results.


Conclusions:
The Decision Tree Regressor is a simpler model with less complexity, while the Gradient Boosting Regressor produced the best predictive results.
Novelty:

We incorporated all columns into our models, including categorical ones, by using various encoding techniques such as One-hot, target, and frequency encoding based on the attributes.

Insights:
 
The use of encoding methods provided insights into how different factors affect predictions. Frequency encoding of locality revealed patterns in location-based outcomes, while target encoding of race names showed performance trends, highlighting how past results can influence future predictions.
        
















