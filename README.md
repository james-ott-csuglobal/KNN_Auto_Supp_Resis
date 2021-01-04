# KNN_Auto_Supp_Resis
unsupervised machine learning support and resistance level selection for stock charts in a notebook...

Idea orginated with https://github.com/judopro/Stock_Support_Resistance_ML but its changed slightly to include auto smoothed levels,
in addition to the original codes high and low clusters.

Imports/Packages:

from sklearn.cluster import KMeans
from matplotlib import pyplot as plt
import matplotlib.ticker as mpticker
from mpl_finance import candlestick_ohlc
import matplotlib.dates as mpl_dates
import pandas as pd
import numpy as np
import yfinance as yf
from datetime import datetime, date
import scipy.stats as si
import matplotlib.pyplot as plt
from datetime import datetime, date
import time


