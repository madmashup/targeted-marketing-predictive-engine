# targeted-marketing-predictive-engine
This project contains a banking dataset from UCI's website. I have created a predictive modeling engine using scikit-learn that will determine if a customer will avail to a Certificate of Deposit(CD) or not.
Logistic Regression with Cross Validation training hyperparameters has been used for modeling and evaluation purposes.

# Installation Notes
This tutorial will require recent installations of numpy, scipy, matplotlib, scikit-learn, psutil, pyrallel and ipython with ipython notebook.

The last one is important, you should be able to type:

ipython notebook
in your terminal window and see the notebook panel load in your web browser. Because Python 3 compatibility is still being ironed-out for these packages (we're getting close, I promise!) participants should plan to use Python 2.6 or 2.7 for this tutorial.

For users who do not yet have these packages installed, a relatively painless way to install all the requirements is to use a package such as Anaconda CE, which can be downloaded and installed for free.

# Data Downloads
The data for this tutorial is not included in the repository. We will be using several data sets during the tutorial: most are built-in to scikit-learn, which includes code which automatically downloads and caches these data.
You can download the dataset from:
Cloud-  https://s3.amazonaws.com/aml-sample-data/banking.csv
        https://s3.amazonaws.com/aml-sample-data/banking-batch.csv

UCI Machine Learning Repository-
        http://archive.ics.uci.edu/ml/datasets/Bank+Marketing

# Pre-requisites
1)Basic Python knowledge
2)Machine Learning Concepts
3)Familiarity with python libraries such as numpy,scipy, pandas etc.

# Getting Started
scikit-learn provides various methods to model and evaluate Machine Learning concepts in Python. scikit-learn is an umbrella consisting of libraries such as numpy, scipy, pandas and matplotlib(for plotting). Pandas has generally been used for Data munging, cleansing and preprocessing. 
scikit's excellent cross_validation library provides splitting the data into training and test data and preventing overfitting of curve. For our purposes we have done 70/30 split.
Logistic Regression as a model for Binary Classification has been used. 

