# RNNModel-energy-dataset
# Energy Time Series Forecasting with RNN

## Overview

Welcome to the Energy Time Series Forecasting project! This repository contains code for building a Recurrent Neural Network (RNN) model to forecast energy generation,
 incorporating historical time series data and future covariates.


## Introduction

This project leverages deep learning techniques, specifically RNNs, to forecast energy generation.
 It considers historical energy time series data and future covariates to make accurate predictions.

## Setup

### Prerequisites

Ensure you have the required dependencies installed:

# Example command for installing prerequisites
!pip install darts


## Usage
1- Load the energy dataset and preprocess it.

2- Create time series for energy and future covariates.

3- Train the RNN model with historical data and covariates.

4- Make predictions and evaluate the model's performance.

## Model Configuration
The RNN model is configured with the following parameters:

- Model: LSTM
- Hidden Dimensions: 30
- Number of LSTM Layers: 3
- Number of Epochs: 10
- Training Length: 300
- Input Chunk Length: 300
- Dropout: 0.0
- Likelihood: Gaussian


## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
