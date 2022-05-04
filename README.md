# DS-303 Group Project
## Stock Price Prediction using different Regression Techniques

### Introduction

This is the Course Group Project for the Course "DS303 - Introduction to Machine Learning" taken by me as a minor course by CMINDS department at IITB in my 2nd year Spring Semester, Which was taught by the prof [Biplab Banerjee](https://biplab-banerjee.github.io/).

As this was a group project, we were team of 4 members-

1-Niteesh Singh (Me)

2-Bhawana Mahur

3-Aditya Sugriv Kendre

4-Jigmat Chosdol

We build 4 different models to Predict The closing price of the stock namely KNN, SVR, SARIMA, and a model using FNN and CNN.

### Content in this Repository
This repo contains 2 folders namely Data and Models and a file named "report".

#### Data Folder

This Folder Contains the data we used in our models in csv format

It has following 4 files -

AAPL.csv - Historical Data of Apple Stock price - used in our SARIMA model

RELIANCE.NS.csv - Historical Data of Reliance Stock price - used in our SVR model

TSLA.csv - Historical Data of Tesla Stock price - used in our KNN model

TCS.NS.csv - Historical Data of Tata Consulting Services Stock price - used in our FNN and CNN model

All the data was taken from the [yahoo finance](https://finance.yahoo.com/) Website


#### Models Folder

This folder contains the model we build it has 4 "google colab's" .ipynb files

KNN_model.ipynb - model using K-Nearest Neighbours approach 

SVR_model.ipynb - model using Support Vector Regression approach

SARIMA_model.ipynb - model using Seasonal Autoregressive Integrated Moving Average approach

FNN_and_CNN_model.ipynb - model using Feed Forward Neural Network (FNN) and another model using 1-D Convolutional Neural Network (CNN)

The refrence for any code snippet taken from internet is provided in our report or inside code cell in respective model, otherwise 
the whole code was written by us using various python libraries.

#### Report.pdf

As the name suggest it is the report of our project contains all the information from **data collection** , **preprocessing** to **model building**,
**accuracy** of our models and the **refrences used**.
