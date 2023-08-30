![image](https://github.com/dylan860/Machine_Learning_trading_bot/assets/127907809/b1e8f003-47fa-421d-8960-97446ffdd0f6)

# Machine_Learning_trading_bot
This is a code created with a Jupyter Lab Notebook used with the assitance of Pandas to use a deep learning model thats trained and tested in order to further analyze an automated trading Algorithm which sole purpose to to buy on bullish SMA (Simple Moving Average) 

Technologies
This project uses python 3.7 with the following packages:

Pandas - Pandas is an open-source library that offers easy-to-use data analysis tools for Python.

Jupyter Lab - For an intuitive notebook IDE

scikit-learn - For sofisticated machine learning models

[logistic-regression] (https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) - Classifying Model

Installation Guide
Before running the application first install the following:

[Install] Anaconda with Python 3.7+(https://docs.anaconda.com/anaconda/install/) You should always be in a conda dev environment when launching JupyterLab.
Install/Import the following libraries and dependencies
# Install the required libraries
conda install -c conda-forge imbalanced-learn
conda install -c conda-forge pydotplus

# Imports
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
Usage
To view the venture_funding_with_deep_learning.ipynb, open file via Jupyter Lab

cd <location of (venture_funding_with_deep_learning.ipynb)>
jupyter lab
Upon launching the Jupyter Lab NOTEBOOK you will be greeted with the following prompts.
![image](https://github.com/dylan860/Machine_Learning_trading_bot/assets/127907809/68863e15-7d7c-41e6-9141-3795e0caccf8)

 Following is the model/SM comparisons in an attempt to improve the strategies baseline performance
 ![image](https://github.com/dylan860/Machine_Learning_trading_bot/assets/127907809/282b5d03-99f9-4b73-972e-226d856d4875)
 Baseline Performance

![image](https://github.com/dylan860/Machine_Learning_trading_bot/assets/127907809/a0003a96-2162-40d0-8050-f1bb48fa4f03)
length of the SHORT WINDOW (21) and LONG WINDOW (200), this made the strategy performace fall behind actual returns

![image](https://github.com/dylan860/Machine_Learning_trading_bot/assets/127907809/52183259-7179-4ab5-a99a-cc1e7076fb49)

 








