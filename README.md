# Flu-Shot-Learning-Predict-H1N1-and-Seasonal-Flu-Vaccines
The goal is to predict how likely individuals are to receive their H1N1 and seasonal flu vaccines. Specifically, be predicting two probabilities: one for h1n1_vaccine and one for seasonal_vaccine.  Each row in the dataset represents one person who responded to the National 2009 H1N1 Flu Survey. For details please visit the link: https://www.drivendata.org/competitions/66/flu-shot-learning/page/211/

team: Ayse
members: @Aysenuryilmazz, @mustafahakkoz
current rank: 141/1044
score (AUC): 0.8462

In this project to find the best model, we tried to use 5 different regressor algorithms, they are:

- Decision Tree regressor
- Bayesian Ridge
- SVR
- SGD Regressor
- Random Forest Regressor

As a result, 3 of them gave me almost the same score(Bayesian-Ridge & SGDRegressor & RandomForestRegressor), then I applied t-test to find "best one" among them. That was Random Forest Regressor. 

Two output labels(h1n1&seasonal) are merged and produced a .csv file as output. 

Beside, neural network algorithm with 1-layer also applied.


