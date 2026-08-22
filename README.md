# 💎 Diamond Price Analysis & Prediction

A complete data science mini-project exploring what drives diamond prices, and building a model to predict them.

## Overview
This project analyzes a real dataset of ~54,000 diamonds to answer: **what factors actually determine a diamond's price, and how well can we predict it?**

## What's inside
- **Data cleaning**: handling missing values, invalid entries, and duplicates
- **Exploratory Data Analysis (EDA)**: distributions, correlations, and group comparisons using pandas, matplotlib, and seaborn
- **Statistical hypothesis testing**: t-test comparing prices across diamond cut quality
- **Machine learning**: Linear Regression vs. Random Forest for price prediction

## Key findings
- Carat (size) is by far the strongest predictor of price — far more than cut quality
- "Ideal" cut diamonds are, on average, *cheaper* than "Premium" cut ones, which is explained by carat size acting as a confounding variable
- A Random Forest model explains ~98% of the variance in diamond prices (R² ≈ 0.98), significantly outperforming plain linear regression

## Tools used
`Python`, `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`, `scikit-learn`

## How to run
1. Open `diamond_price_analysis.ipynb` in Google Colab or Jupyter
2. Run all cells in order
3. Dataset loads automatically via seaborn — no download needed

## Author
Maheen Fatima — BS Data Science student
