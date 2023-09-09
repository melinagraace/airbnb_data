# Airbnb Cleaning
Melina Wettstein <br>
Last updated: September 7, 2023

## Data
Downloaded from [inside airbnb]{http://insideairbnb.com/get-the-data}, last updated June 23, 2023. 

## Goals of project
Currently, this is the first part of a project on creating a machine learning model for airbnb data from Vienna, Austria. 

This parts demonstrate cleaning messy data with pandas. The ultimate goal would be to go onto use this data in machine learning algorithms. Note that some of this cleaning is for exploratory and demonstative purposes and should be done more efficiently via Pipelines after splitting the data to avoid issues of data-leakage. 

## Software
Jupyter notebook <br>
python packages: <br>
import pandas as pd<br>
import numpy as np<br>
import matplotlib as mpl<br>
import matplotlib.pyplot as plt<br>
from sklearn.impute import SimpleImputer <br>
from sklearn.preprocessing import OneHotEncoder
