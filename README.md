# Python For Data Analysis

This is a supporting codebase for data analysis courses in [MS in Business Analytics](https://www.ceu.edu/academics/degrees/ms-business-analytics) at the Central European University. 

## Overview

The codes follow and supplement the textbook **Data Analysis for Business, Economics, and Policy** 
by Gábor Békés (CEU) and Gábor Kézdi (U. Michigan),  Cambridge University Press, 2021. 

Note: this is an alternative to the book's original coding material: [da-coding-python](https://github.com/gabors-data-analysis/da-coding-python/tree/main). 

The reason for this repo was to create a downloadable coding course content which any instructor can rely on to follow the book's topic, almost on a chapter-by-chapter basis. 

The content is broken down to essentially two parts.

- Classes 00-06 introduce major concepts in Python, including using Python on the user's laptop. These classes do not follow the book's first six chatpers, rather, as students are picking up the theory, it is preparing them for using Python's tools for data analytics. Class 06 is a standalone analytical exercise, the topic of which ([Premier League 2021/22 matches](https://www.premierleague.com/en/tables?competition=8&season=2021&round=L_1&matchweek=-1&ha=-1)) is not covered in the book.
- Classes 07-18 rigorously follow the book's syllabus. These classes take the reader through the analytical workflow covered in the book. Most (but not all) of the chart and table outputs reproduce visualizations in the book. 

## How to use

The course material does not require any previous knowledge of Python or computer programming in general. The first seven classes introduce basic programming concepts and their implementations in Python. These classes won't make anyone a programmer but completing them will prepare the user for his/her data analysis journey in Python.

It is difficult to interpret the classes by themselves without reading and undertanding the underlyng course material in **Data Analysis for Business, Economics, and Policy**. By reading the codebase *and* the book's chapters in a paralell fashion, nevertheless, will help the reader put the pieces in their places. 

## Course content

| Class &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   | Main points & learning outcomes |
| -------- | ----------------- |
| [Class 0](class-00-setting-up-your-data-science-environment) | How to setup the environment; Python, Jupyter notebooks, virtual environments |
| [Class 1](class-01-coding-basics) | coding principles, variables, basis operations |
| [CLass 2](class-02-io-and-utilities) | files & file system, time-related variables, error handling |
| [Class 3](class-03-udfs-classes-numpy) | user-defined functions, numpy, classes |
| [ Class 4](class-04-pandas) | Pandas dataframes |
| [Class 5](class-05-plotting) | charts |
| [Class 6](class-06-data-analysis-with-python) | How to do data analysis in Python? A hands-on exercise |
| [Class 7](class-07-simple-ols) | simple linear regression |
| [Class 8](class-08-complicated-patterns) | compicated regression patterns: non-linear relationships and data transformations |
| [Class 9](class-09-generalizing-regression-results) | generalzing regression results, comparing optional regression models, visualizations and output | 
| [Class 10](class-10-multiple-linear-regression) | multiple linear regression, using `statmsmodels` and `stargazer` for tidy regression outputs | 
| [Class 11](class-11-probabilities) | modelling probabilities, assessing their performance, calculating marginal effects | 
| [Class 12](class-12-time-series) | time series regressions, intricacies of time series modelling, handling seasonal patterns | 
| [Class 13](class-13-framework-for-prediction) | a framewrok for  comparing and presenting multiple linear regression model options | 
| [Class 14](class-14-model-building-for-prediction) | first venture into machine learning: `lasso`, cross-validation, and the `scikit-learn` library |
| [Class 15](class-15-regression-trees) | building and visualizing classification and regression trees |
| [Class 16](class-16-random-forest-and-boosting) | `random forest` models, introducing `gridsearch` and hyperparameter tuning | 
| [Class 17](class-17-probability-and-classification) | estimating probablities using linear and non-linear models (`logit`), introducing AUC and the ROC curve| 
| [Class 18](class-18-time-series-predictions) | modelling deterministic and stochastic time series, ARIMA, `fbprophet`


## Note

Feel free to use the codes as you wish, in their current or in any modified form. 