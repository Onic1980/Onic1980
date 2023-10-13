# ReadMe file for SAMAI notebook Zindi
This file explain how to run Google Colab notebook SAMAI_notebook_Zindi_shortData_Fin


#Paths
- To set paths to  files and models you need change the paths in cell of Google Colab notebook with ref # #setting paths for files 

#Order in which to run code
- You need run  cells in the noutbook in order of following each other

#Explanations of features used
- To predict CPI categories I use only historical data of CPI categories and fixed weghts of each category

#Environment for the code to be run
You need to import:
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt ( just for visualization of model training. This library don't need in inference mode)
- datetime as datetime ( to covert data to datatime)
- from sklearn.metrics import mean_squared_error (for model evaluating)
- from tensorflow.keras.layers import Input, Dense, BatchNormalization,Dropout
- from tensorflow.keras.models import Model,load_model
- from tensorflow.keras.preprocessing.sequence import TimeseriesGenerator
- from tensorflow.keras.optimizers import Adam
- from tensorflow.keras.callbacks import EarlyStopping,ReduceLROnPlateau,ModelCheckpoint ( need only for model training, don't need in inference mode )

#Hardware needed
-To run this code yuo need only Google Colab

#Expected run time for notebook.
- it takes near 38 sec to run



###End
