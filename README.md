# Short-Term Cryptocurrency Price Prediction and Inequality Analysis

This project explores the application of machine learning (ML) models for cryptocurrency price prediction, leveraging mathematical and statistical measures such as the Gini Index and Kolkata Index to enhance prediction accuracy. By analyzing the inequality and volatility of cryptocurrency price distributions, the study provides insights into the complex dynamics of these markets.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Data Collection](#data-collection)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [Future Work](#future-work)
- [Contributors](#contributors)

## Introduction
Cryptocurrency markets are highly volatile and decentralized, making price prediction a challenging task. Traditional ML models often fail to capture these complexities. This project introduces new feature engineering techniques, incorporating inequality measures and statistical metrics to improve the predictive performance of ML models.

## Features
- **Inequality Measures:** Gini Index, Kolkata Index.
- **Statistical Metrics:** Mean, standard deviation, kurtosis.
- **Machine Learning Models:** Linear Regression, Random Forest, Decision Trees, K-Nearest Neighbors (KNN).
- **Evaluation Metrics:** R² Score, Mean Squared Error (MSE).

## Data Collection
Historical cryptocurrency price data (Bitcoin) spanning 2012–2024 was sourced from [Investing.com](https://www.investing.com). The dataset includes:
- Date
- Opening and closing prices
- High and low prices
- Percentage changes
- Trading volumes

Additional features like Gini Index and Kolkata Index were derived from this data for better prediction.

## Methodology
1. **Data Preprocessing:** Normalization and calculation of derived features.
2. **Exploratory Data Analysis (EDA):** Visualization of time-series data, rolling mean, standard deviation, and Lorenz curves.
3. **Feature Engineering:** Incorporation of inequality and statistical measures.
4. **Model Training:** Training and testing various ML models on the enhanced dataset.
5. **Evaluation:** Comparison of model performance based on R² and MSE scores.

## Results
- **Best Model:** Linear Regression
  - R² Score: 0.9993
  - MSE: 184,970
- The inclusion of inequality measures significantly improved predictive accuracy compared to models trained on the original dataset.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository.git
