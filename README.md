# SL-project
My Statistical Learning project on Pokemon. 

I have developed a statistical model able to solve a regression task, to predict the catch rate of a random pokémon, and a classification task to predict wether or not it is legendary. 

In order to do so I have followed the classic validation procedure by splitting the datasets in training and test (2/3 and 1/3 of records, respectively) and by using the latter to choose the 'best' model for both tasks. 

To solve the regression task I have implemented a battery of generalized additive models, ranging from the simpler linear and polynomial models to the more complex natural or thin-plate splines. In this way I tried to capture high non-linearities in the relationship between my target variable (catch rate) and the set of regressors (like the pokemon combat stats). 

To solve the binary classification task, instead, I tried 3 main types of modelling techiniques: regression (logistic), trees (classification tree, boosting, random forest) and discriminant analysis (linear and quadratic). Data suggests that the pokemon's catch rate and its attack are the most explicative factors to determine wether or not it is legendary.

The dataset is downloaded from Kaggle and all credits for it goes to the user alopez247 (https://www.kaggle.com/alopez247/pokemon). 


