Hello! In this rep you you'll find deep learning templates that I ued to help me understand linear regression for a Deep Learning course at Pace.  These are just templates (featuring a regression example) using:


pip install scikit-learn==1.1.3
     
import sklearn
from sklearn.neural_network import MLPRegressor
from sklearn.model_selection import train_test_split
from sklearn.datasets import fetch_california_housing
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import r2_score
import pandas as pd
     
also extracted from
#sklearn datasets
# https://scikit-learn.org/stable/modules/classes.html#module-sklearn.datasets
# Kaggle dataset
