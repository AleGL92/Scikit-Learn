# Scikit-Learn
There are 3 codes in this repository. They show the process to get price predictions for houses in the Melbourne dataset from Kaggle.
https://www.kaggle.com/dansbecker/melbourne-housing-snapshot/data

Like I did in other repositories, the CSV is uploaded here and the code includes the link, so just downloading the code it can run locally whithout having to download the CSV.

In the first code (Melb_preds.ipynb), there is a basic prediction of house prices, splitting train and test data. I also check the number of nodes in the decission tree regressor, with the mean absolute error function.

In the second code (Melb_preds_2.ipynb) I try to improve the previous results using different ways to handle missing values, such as dropping rows, dropping columns or using imputation. I also try to improve results handling categorical variables with ordinal encoding, one-hot encoding. Finally, there are some pipelines examples, to do some of the previous methods at the same time but just in a few lines.

In the third code (Melb_preds_3.ipynb) I use cross-validation and XGboost to improve results a bit more.

There's also a test I took, to predict if a bank's clients will be paying their debt. It's done using Scikit-Learn too.
