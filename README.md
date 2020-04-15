# Covid-19-Test-performance

# LIBRARIES
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import cx_Oracle
from sklearn import preprocessing
import scipy as sp
from sklearn.cluster import KMeans

# Motivation:
I would like the bring a new perspective to how the countries are managing the covid-19 pandemic.

# Data sources:
Most the data I have used is extracted from the ourworldindata.org.
You can find the data set in the csv file that I shared.
Data includes, Countries test,case,death numbers by daily. Also it has population and GDP numbers of the countries.

# Results:
Case numbers are related to Test numbers and the test numbers are related to wealth of the country.
So if we want to see testing performance of the countries we need to include welath and population metrics. If only this way we can measure the real power of the cuntries over handling the covid-19 pandemic.
