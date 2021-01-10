# Overview

PySpark project aiming at predicting the success of a kickstarter campaign based on the Kaggle dataset available [here](https://www.kaggle.com/kemical/kickstarter-projects).

The project relies on **Apache Spark** and includes:

1. a full Machine Learning pipeline (data processing and modeling)
2. a data loader (to read and transform the data)
3. 5 machine learning models using cross-validation or a train-test split
4. 2 discontinued section related to implementing a dense neural network using Elephas and BigDL (issue regarding environment on Google Cloud)

Two notebooks are available: one run locally and one run on Google Cloud Dataproc.
