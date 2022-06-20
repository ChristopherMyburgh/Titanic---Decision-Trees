# Titanic---Decision-Trees
Using multiple Decision tree methods on the Titanic Dataset

I performed a quick data exploration to ascertain if there were any missing values and how the data was spread. When missing values were found, I performed Imputation on the numeric values that could be averaged, and for the categorical values, I imputed the data with the most common occurence.

I created 4 different Decision Tree models. 
  1. Standard Decision Tree
  2. Bagging
  3. Random Forest
  4. Boosted Trees

Each tree, a accuracy score was calculated and I went further to tune the hyperparameters of the Random Forest Model. I adjusted the max-depth, the minimum samples per branch and the n estimators of the model. Once Tuning was complete, I deployed the model onto a test set.

Each model was deployed onto a test set and their accuracy scores were compared with one another at the end. 

The Boosted Tree model performed the best achieving a accuracy score of 80.81%
