# Study_Datascience

## 1. Linear Regression

* SST(total) = SSR(explained) + SSE(unexplained)

* OLS (ordinary least squares) model - minimum SSE [lowest error]

* R-squared = SSR/SST (measure how much of the total variability of the dataset, ranging 0 to 1 variability)

## 2. Multiple Linear Regression

* adjusted R-squared (<R-squared) measures how well your model fits the data, but it penalizes the use of variables that are meaningless for the regression

* increases R-squared but decreases adjusted R-squared ⇒ omit the variable

## 3. Logistic Regression
-> The logistic regression predicts the probability of an event occurring

* Maximum likelihood estimation (MLE) : estimates how likely it is that the model at hand describes the real underlying relationship of the variables

* LL-null ( log likelihood-null) : the log-likelihood of a model which has no independent variables

* LLR(log likelihood ratio) : measures if our model is statistically different from LL-null
