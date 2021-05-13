# Deterministic-and-Probabilistic-Regression
Study involving a challenging multivariate regression problem that explores deterministic regression first and then explores the use of probabilistic regression to get a better feel of the uncertainty in the predictions

The problem at hand is predicting average monthly spend on product by future customers, which due to the continuous nature of the target variable requires a supervised regression algorithm to solve.

We start with three separate data sets and we use Pandas to join all the data together and to wrangle the data in a way that the features benefit the regression problem optimally.

There are multiple features and data is further explored with Pandas to determine which features usefully explain variance in the target variable.

Binning is used to enhance the usefullness of continuous numerical features like age and to improve categorical ones

Categorical features are one hot encoded and this process expands the feature count and the feature matrix size, for this reason feature selection using Sci-kit Learn is necessary in order to reduce and optimize the size of the data set.

Additional numerical feature transformation is performed and test train splits are created also using Sci-kit Learn.

The handling of the data makes it possible to obtain robust results with simple multiple linear regression. However, considering multiple feature transformations and assumptions made during modeling, a better feel for the uncertainty of the model is explored using TensorFlow probability.

Two dimensional models, fixed variance models, and models with uncertainty in the weights are explored along with ideas on how to incorporate into serving predictions

Many thanks to Sergey Karayev, Josh Tobin, Pieter Abbeel and team at University of California Berkeley for encouraging us to challenge ourselves with this project and Kevin Webster and team from Imperial College London for a fresh perspective on ideas on the use of TensorFlow Probability to create probabilistic regression models

![image](https://user-images.githubusercontent.com/54419767/118192542-e97f3500-b40b-11eb-99b1-b3f9cf5c4b49.png)
