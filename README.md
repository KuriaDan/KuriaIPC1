# KuriaIPC1
Prediction algorithm for which individuals are most likely to have or use a bank account in Kenya, Uganda, Tanzania, Rwanda

Prerequisites

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt   # Data visualisation libraries 
import seaborn as sns
%matplotlib inline
from sklearn.linear_model import LinearRegression
from sklearn import model_selection
from sklearn.metrics import r2_score
from sklearn.model_selection import train_test_split
import statsmodels.api as sm
%pylab inline
matplotlib.rcParams['figure.dpi'] = 300
matplotlib.rcParams['figure.figsize'] = (8,6)
from biokit.viz import corrplot
import pandas_profiling as pp


Data Sourcing The project began with the sourcing/collecting of dataset to be used for analysis. We sourced our dataset from data.world. According to the website the origin of the dataset was http://opendataforafrica.org/dqoksbf/african-regional-energy-statistics-2014
Data Preparation and Quality Data Selection: We dropped the region column because it was unnecessary for our analysis.
Data Cleaning: We converted the column names to lowercase to ensure uniformity of the column names in the dataset. We checked for duplicate and null values in the dataset and found none. The Region column was dropped from the dataset as it invalid for the analysis. We selected only the rows whose regionname was Kenya and East Africa in order to work with a smaller dataframe.

