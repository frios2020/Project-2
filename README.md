Project 2: NYC TAXI FARE PREDICTION PROJECT
===========================================

NJIT Data Science Program<br>
Course<br>
CS634 Data Mining - Summer 2020<br>
Instructor Pantelis Monogioudis, Ph.D Professor of Practice, NJIT & Adjunct NYU<br>
Teaching Assistant Michael Lam (PhD student)

Students:<br>Fernando Rios<br>Hassan Ouanir<br>Ian Kavuma

Introduction:

In this project, the task is to predict the taxi fare in New York City given the information about number of passengers, pickup and dropoff locations, and the pickup datetime. The NYC TAXI FARE dataset consists of 55 million training records since 2009 and 9914 test records which represent taxi trips in New York.To achieve this goal predicting NYC Cab fare, we split this project into three parts:

**Part I** : Data pre-processing and Exploratory Data Analysis (EDA)
*Data cleaning, data Exploration
*Data visualization, and
*Feature engineering, Feature Selection

**Part II** : Predictive Modelling
*Model Evaluation

**Part III** : Submission

###Setup
This notebook is prepared to run easily, just copy the files:
kaggle.json, nyc_mask.png and, boxdefined.png in your google drive, after that, open the file NYC TAXI FARE PROJECT/NJIT.ipynb

select option run all in google colab. 
In its lines this notebook do these steps to have ready the dataset.

```python
# Import Libraries
from google.colab import files
import os
import sys
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from IPython.display import Markdown, display
import datetime as dt

from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error
from sklearn.linear_model import LinearRegression

# Installing kaggle
!pip install kaggle

# Mounting google drive
drive.mount('/content/drive/')

# Move kaggle.json from Google Drive to folder Kaggle
!mkdir -p ~/.kaggle
!cp /content/drive/My\ Drive/kaggle.json  ~/.kaggle/kaggle.json

# Downloading dataset from Kaggle
!kaggle competitions download -c new-york-city-taxi-fare-prediction

# List all files in the folder where the data was downloaded
print(os.listdir())

```

After this, you can go through the all parts of the project: 
Part I: Data pre-processing and Exploratory Data Analysis (EDA)
Part II: Predictive Modelling
Part III: Submission


All contributions are welcome!
In this project, the task is to predict the taxi fare in New York City given the information about number of passengers, pickup and dropoff locations, and the pickup datetime. The NYC TAXI FARE dataset consists of 55 million training records since 2009 and 9914 test records which represent taxi trips in New York.

To achieve this goal predicting NYC Cab fare, we split this project into three parts:

Part I: Data pre-processing and Exploratory Data Analysis (EDA)
ta cleaning, Data Exploration
ta visualization, and
Îture engineering, Feature Selection

Part II: Predictive Modelling
Î
Taxi Fare Prediction

