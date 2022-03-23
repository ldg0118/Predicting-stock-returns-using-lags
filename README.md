# Predicting-stock-returns-using-lags
Predicting stock returns using lags with regression models

We have always been wondering how the lagged stock returns explain the real stock return so in this report, supervised machine learning models with Ridge regressions are come up with to make predictions of stock returns using 5 previous-day stock returns. The entire model building process starts with a data overview, and is followed by a simple stock model built with only one stock and finally a general stock model built with several stocks after taking consideration of the fixed effect inside each stock through one-hot encoding. 5-fold cross validation is used for selecting the optimal parameter in the loss function. And this report will be structured by discussing data in the Data section, model in the Model section, results in the Result section, and limitations in the Limitation Section. 

This repository contains a pdf report of the final model and also a r-markdown file detailing the r codes to realize this.
