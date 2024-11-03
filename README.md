#  Stock Price Prediction

This project uses Long Short-Term Memory (LSTM) neural networks to predict Tesla (TSLA) stock prices. The dataset is fetched from Yahoo Finance and preprocessed using MinMax scaling for training on sequential data, allowing the model to learn from historical stock prices to predict future values.

## Table of Contents
- [Installation](#installation)
- [Project Overview](#project-overview)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training and Evaluation](#training-and-evaluation)
- [Visualization](#visualization)
- [Results](#results)

## Installation

To run this project, you’ll need Python and the following libraries:

```bash
pip install tensorflow numpy pandas yfinance scikit-learn matplotlib
