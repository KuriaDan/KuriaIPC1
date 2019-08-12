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



