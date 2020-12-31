🥣

View the notebook [here](https://www.kaggle.com/gracecmy/predicting-cereal-preferences-with-knn-regression) if there are any plotly figures not showing up!

Using scikit-learn's knn regressor to predict cereal preferences.

The optimal number of neighbours to accurately predict a cereal's rating was explored and, in this case of 80 cereals, was 5. Feature selection (SelectKBest and f_regression) was also conducted to improve the model's accuracy from 72% to 91% with the actual and predicted results not rejecting the null hypothesis and having a similar mean and standard deviation, the same maximum value and acceptable kurtosis (the acutal and predicted results differ is a larger predicted minimum value and a more skewed predicted distribution).

General description and data are available on [kaggle](https://www.kaggle.com/crawford/80-cereals).
