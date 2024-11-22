# PyTorch Exercises  

## 1. Regression with the Penguins Dataset  
Use the `penguins` dataset available in the `seaborn` library to build a regression model with PyTorch.  

The goal is to predict the body mass (`body_mass_g`) of penguins based on attributes such as bill length (`bill_length_mm`) and bill depth (`bill_depth_mm`).  

Load the dataset using `seaborn.load_dataset('penguins')`, then train a linear model and evaluate the results on the test set. Afterward, train a non-linear model and evaluate the results on the test set.  

> Why does this difference exist?

## 2. Classification with the Iris Dataset  
Train a classification model with PyTorch to predict the species of each flower in the Iris dataset based on its features.  

To do this, load the dataset using the `load_iris()` function available in `sklearn.datasets`;