# LANL earthquake prediction
kaggle competition @ https://www.kaggle.com/c/LANL-Earthquake-Prediction

### Python project summary

- Prepared dataset acoustic signals from earthquake simulator
- Conducted statistics-driven engineering of 100 features
- Developed 11 regressor algorithms to predict time to failure (earthquake)
- Fine-tuned top performers incl. grid search and visualized performance
- Developed a stacked model and evaluated added value

![sample_failure](https://github.com/manuelfreude/kaggleearthquake/blob/master/sample_failure.png)

### Project results

The top-performing algorithms Gradient Boosting, Bagging, Support Vector Regressor (SVR) and AdaBoost achieved very similar mean absolute errors (MAE). Improving performance by only a tiny fraction was not trivial and did not always lead to higher scores at kaggle. AdaBoost (tuned) delivered the best predictions for the kaggle scoring.

![Results](https://github.com/manuelfreude/kaggleearthquake/blob/master/earthquake_results.png)

Stacking the models either in the combination of Gradient Boost/Bagging/AdaBoost or SVR/Bagging/Adaboost and running a linear regression with the prediction input of these three did not result in improved MAE compared to singular models.

The initial submission ranked 455 out of 2,032, or top 23%, the best result I obtained during a competition so far!! Posting this on LinkedIn achieved 1,400+ views of my network, both great achievements!!


![kaggle_i](https://github.com/manuelfreude/kaggleearthquake/blob/master/kaggle_performance_earthquake.png)

### Conclusion / further improvements

The earthquake prediction results show how important statistical feature engineering can be, even if the understanding of the causes why certain features influence predictions are limited. In this competition and beyond, thorough data analytics can not only provide highly effective predictions, but also point business or research to new areas of investigation that might not have been explored before.

### Final kaggle score to be added once competition is finished
