# Heart-Attack-Prediction-Part2
This repository is a continuation of my work from my graduate class DSE6111, where I used predictive models to predict heart attacks, and test each models accuracy. In this repository, I switch to Python from R and test some other advanced models including a couple different neural networks from sklearn and pytorch.
<li>Ryan Canfield - canfieldr@merrimack.edu
  
## Requirements
#### Software
Python IDE,  Jupyter notebooks

#### Packages
pandas, pumpy, seaborn, matplotlib.pyplot, os, statsmodels, warnings, torch, torch.nn
from torch.utils.data -- Dataset
from sklearn.model_selection -- train_test_split
from sklearn.preprocessing -- MinMaxScaler 
from sklearn.neural_network -- MLPClassifier 
from sklearn.metrics -- confusion_matrix, ConfusionMatrixDisplay, accuracy_score

#### How to run
If you copy this repository to your local computer everything should run after other requirements are met.
You may need to adjust file paths due to it being on a different machine and not using arelative path.
All .csv files are part of the repository and will load into their respective jupyter file.

## Dictionary
#### The three important files to run are..
<li>Machine Learning Project 3.ipynb - Code that cotains nueral network models.

#### .csv files
<li>heart.csv -- Dataset containing paitents with heart disease found on kaggle -- https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset?select=o2Saturation.csv
Final Report
<li>modified_heart.csv - Dataset that was changed inside the python file.
