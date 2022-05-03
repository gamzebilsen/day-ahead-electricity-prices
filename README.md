# Electricity Price Forecasting: Day-Ahead Price prediction in PJM using Deep Learning
This project uses deep learning methods to predict day-ahead electricity prices in the PJM region. The goal of this project is to test out different deep learning methods to improve the accuracy and generalizability of the models used to predict the prices.

## Data Sources
PJM's Data Miner:
1. Day-Ahead Pricing
2. Load Forecasting
3. Transmission Constraints

## Installation
You can download the datasets and the example code to run the models in addition to the exploratory data analysis. The thought process choosing some data over the other or adding in binary variables such as day of week are further discussed in both the html and the pynotebook version.

## Usage
Final Model Results

![image](https://user-images.githubusercontent.com/50467434/166561585-a9822890-ab05-4dd6-8658-ff7f64c0c164.png)


The final model shows a relatively high accuracy for train and validation sets. Looking at the test set, it does more or less tend to fall within the actual data, however does at some times lie beyond the region of the actual data. However, given the performance of the other models, this one is the best one since the predicted pricing values also have similar, although slightly less, variation as the actual price data. 

## Roadmap
I have found that the RNN models such as RNN, GRU and LSTM tend to take a lot more computation time and produce much less accurate results. However, it is recommended that the data be changed such as adding in more data or removing some to make the data less restrictive, and the time steps can also be altered. Additionally, there are many more things that can be tested to try to improve both the RNN and the DNN models - one can reference the example code for insights into what can be tested. Additionally, the recommended LEAR models can be tested as well.
