The coding file are split into two parts with 4 files

The first part is about scraping the data from the website luxstay.vn
there are two files in this part
1. "Proper Scraping.ipynb": a script that scrape the data
2. "Cleaning Luxstay Data.ipynb": clean the data format, make it able to manipulate, analyse and model

The second part is the modelling part
there are two files in this part
1. "Data_preprocessing_exploration.ipynb": this file contains a script about converting some categorical values
from Vietnamese words to words in English alphabet and sketch some graphs for visualisation. Finally, it derives dummy 
variables to run the model
2. "Implementing_models": the file contains a scipt about running the proposed models. I wrote my own version of FISTA for LASSO
and K-Fold CV to run LASSO and Neural Networks

Required: Jupyter Notebook as IDE for Python
Package used: numpy, pandas, sklearn, pytorch, xgboost, lightgbm, selenium, bs4, time, datetime