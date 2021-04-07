# Dynamic-Programming

## Implemented Decision Tree model using Component Wise Gradient Boosting Algorithm in Python

• The gradient boosting algorithm for decision trees (DT) works by sequentially adding DT's to an ensemble, each DT correcting its predecessor DT's error; each tree makes use of all the predictors available at each step, prediction is calculated by summing up predictions made by all trees
• Implemented algorithm also follows the same process but with a modification. While fitting a single new decision tree in order to predict the residual errors, we first fit multiple decision trees using fixed subset of independent variables and then select the one having least sum of squared residuals.
• The tree with the lowest sum of squared residuals (SSR)is used in making the prediction. Likewise we sequentially add up the trees by the above process and for the final prediction we sum up the offset value and the predictions made by the subsequent trees ( ones selected having least SSR ) factored by learning rate to avoid overfitting.

Reference:
Greb, F. and Prakash, A. (2017). Assessing volatility patterns in food corps. FAO Commodity And Trade Policy Research Working Paper Series, No 53.

Link: http://www.fao.org/3/a-i7066e.pdf
