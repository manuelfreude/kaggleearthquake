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

![grad_grid](https://github.com/manuelfreude/kaggleearthquake/blob/master/grad_grid.png)

The top-performing algorithms Gradient Boosting, Bagging, Support Vector Regressor (SVR) and AdaBoost achieved very similar mean absolute errors (MAE), raising the bar only by a tiny fraction was not trivial and did not always lead to higher scores along kaggle scoring. AdaBoost in the end provided the best predictors for the kaggle scoring,

![Results](https://github.com/manuelfreude/kaggleearthquake/blob/master/earthquake_results.png)

Stacking the models either in the combination of Gradient Boost/Bagging/AdaBoost or SVR/Bagging/Adaboost and running a linear regression with the input of these three did not result in an improved MAE compared to singular models.

The initial submission ranked 455 out of 2,032, or top 23%, the best result I obtained during a competition so far!! Posting this on LinkedIn achieved 1,200+ views of my network, both great achievements!!

![kaggle_i](https://github.com/manuelfreude/kaggleearthquake/blob/master/kaggle_performance_earthquake.png)

### Conclusion / further improvements

This project is part three of my kaggle competition track. I started with the petfinder pet adoption speed prediction (initial submission top 82%), applied learnings and developed further improvements for the Santander customer transaction prediction (initial submission top 57%) and again applied learnings and new code snippets for the LANL earthquake prediction (initial submission top 23%). These are great results and great improvements for being a starter.

The earthquake prediction results show how important statistical feature engineering can be, even if the understanding of the causes why certain features influence predictions are limited. In this competition and beyond, thorough data analytics can not only provide highly effective predictions, but also point business people or researchers to new areas of investigation they might not even have thought about before.

### Final kaggle score to be added once competition is finished
