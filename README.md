# Kaggle-RegressionwithInsuranceDataset

This repository contains the code used in training a model to predict insurance premiums for a Kaggle Competition.
Link to Competition: https://www.kaggle.com/competitions/playground-series-s4e12
Link to Dataset: https://www.kaggle.com/datasets/schran/insurance-premium-prediction

The following imports are needed for running the code:
- import numpy
- import pandas
- import matplotlib.pyplot
- import os
- from google.colab import drive
- import matplotlib.scale as mscale
- from sklearn.linear_model import LinearRegression
- from sklearn.metrics import root_mean_squared_log_error as rmsle
- import torch
- from torch import nn
- from torch.utils.data import DataLoader as DataLoader
- import torch.optim as optim
- from torch.utils.data import TensorDataset

