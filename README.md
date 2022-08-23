# Predicting-Air-Quality-using-AR-model

Predicting Air Quality (PM2.5) readings using AutoRegressive Model from statsmodel.

This Project is created to build a model that predict the PM2.5 readings using AutoRegresssive model from statsmodels. In this project we tune our hyperparameter to improve model's performance. Walk Forward Velidation is perfomed for evaluation of our model.

This Repo include following files
- **README.md:** This file, which contains a summary of files used for this project
- **AutoReg.ipynb:** python notebook where all the task has performed on our data
- **p2.csv:** Our first csv file, from where we are getting our data

## Getting Started
### Environment
* pandas
* matplotlib
* seaborn
* sklearn .metrics
* pytz
* plot_acf and plot_pacf from statsmodels
* AutoReg from statsmodels

### Installing
* you can download our AutoReg.ipynb and the p2.csv files from the repository.
* Now you can run this programm on jupyter notebook, any python notebook or any python IDE.
* Before running programm you have to specify your file path in wrangel function (file path where you have downloaded p2.csv files).
```
df = wrangel("F:filepath/p2.csv")
```
