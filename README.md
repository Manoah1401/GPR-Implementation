# **S&P 500 Prediction using Gaussian Process Regression (GPR)**

## **Project Overview**

This project focuses on predicting the S&P 500 index trends from 1928 to 2018 using Gaussian Process Regression (GPR). It covers the implementation of GPR models, both using sklearn's library and manual statistical calculations, to predict stock market trends and gain insights into the strengths and limitations of GPR in economic forecasting.

## **Files**
1) correc Project Work Report: Project Report for reference
2) Market Returns 1928-2018.csv: Historical S&P 500 dataset used for training and testing the models.
3) S&P500.ipynb: GPR implementation using the sklearn package.
4) S&P500_calc.ipynb: GPR implementation using statistical formulas for mean and variance.
5) noise.ipynb: GPR implementation considering noisy data.
6) sine_wave.ipynb: GPR prediction on a sine wave using sklearn's GPR package.
7) sine_wave_calc.ipynb: GPR prediction on a sine wave using statistical calculations.

## **How to Run**

1) Open any of the .ipynb files in Jupyter Notebook.
2) Follow the steps to import the dataset (Market Returns 1928-2018.csv), train the GPR models, and view the results.
3) Modify the noise parameters or train-test splits to experiment with different data configurations.

## **Dependencies**

1) Python 3.x
2) Jupyter Notebook
3) Libraries: numpy, matplotlib, sklearn

## **Project Goals**

1) Understand the workings of Gaussian Process Regression.
2) Predict and analyze trends in the S&P 500 index.
3) Compare the sklearn-based GPR with manual statistical calculations.

## **Results**

GPR worked effectively for interpolation tasks but faced challenges in extrapolating unknown data points, such as predicting the 2009 recession based on the Great Depression data.
