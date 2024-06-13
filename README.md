# PIC16B-Project

This repository contains the code and documentation for our final project for PIC 16B, focusing on the use of various machine learning models and optimization techniques for portfolio optimization. Our project aims to develop a model that optimizes stock portfolio selection based on projected risk and return.

## Group Members
- Linzhi He
- Tim Li
- Michael Thompson

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Discussion](#discussion)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Member Roles](#member-roles)

## Introduction
In the world of finance, choosing the optimal weight to invest in each stock is crucial for maximizing returns and minimizing risks. This project explores various machine learning models and portfolio optimization techniques to predict and optimize stock weights in a portfolio based on risk and return projections.

## Dataset
The dataset includes historical stock data from the Yahoo Finance package (`yfinance`). It features daily open, close, high, low, and volume data, focusing on the closing prices for effective modeling.

## Methodology
Our methodology encompasses:
- **Data Preprocessing**: Standardization and normalization using MinMaxScaler to prepare data for LSTM models.
- **Model Selection**: Implementation of LSTM, Random Forest, and Linear Regression models.
- **Optimization Techniques**: Mean-Variance Optimization, Advanced Mean-Variance Optimization (CVaR), Hierarchical Risk Parity, and Black-Litterman Model.
- **Hyperparameter Tuning**: Using Random Search for optimizing model parameters.
- **Feature Engineering**: Creating sequences for LSTM and scaling features.

## Results
We evaluate our models based on various performance metrics such as Sharpe Ratio, Return Rate, Risk, and Max Drawdown. Detailed results and visualizations are provided to compare the effectiveness of different portfolio strategies.

## Discussion
The analysis includes a comparison of our models against existing work, with insights into the strengths and weaknesses observed in our approach.

## Conclusion
Summary of key findings and their implications for portfolio management, highlighting the potential of machine learning in enhancing portfolio performance.

## Future Work
Suggestions for integrating dynamic risk preference indicators, real-time data on market volatility, and potentially using reinforcement learning for continuous portfolio optimization.
