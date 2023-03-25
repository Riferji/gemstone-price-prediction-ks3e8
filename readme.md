# Intro
This code was developed for participate in the Kaggle competition *Playground Series - Season 3, Episode 8* (link [here](https://www.kaggle.com/competitions/playground-series-s3e8)), where the objective is predict the cubic zirconia price from several gem characteristics.

The data for this competition (both train and test) was generated from a deep learning model trained on the Gemstone Price Prediction dataset (link [here](https://www.kaggle.com/datasets/colearninglounge/gemstone-price-prediction)).


# Summary
All the code was developed using JupyterLab and was written in Jupyter Notebooks which can be found in the folder *notebooks*. In each notebook, its defined a part of the process:
+ 1_initial_eda: in this notebook, the investigation of the problem and the exploratory data analysis was performed. Additionally, several outliers and incorrect measurements were corrected in the data.
+ 2_feature_engineering: in this notebook, new features were defined for the original data, including an optimization process to calculate new features.
+ 3_base_models: in this notebook, several benchmark models were defined to generate a kaggle submission set.
+ 4_keras_model: in this notebook, a tensorflow model was defined using keras.


# TODO
+ Parallelize the optimization loop
