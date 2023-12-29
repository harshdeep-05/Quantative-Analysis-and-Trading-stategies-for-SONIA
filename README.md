# Quantative-Analysis-and-Trading-stategies-for-SONIA
This project implements a pairs trading strategy using historical data from SONIA (Sterling Overnight Index Average) futures contracts. The primary focus is on the relationship between two specific contracts, namely SONIA Mar24 and SONIA Jun24. The data was downloaded from yahoo finance and was analysed using python.

Key Features
Spread Calculation: Computes the spread between SONIA Mar24 and SONIA Jun24 contracts.
Z-Score Calculation: Computes the Z-score of the spread to identify deviations from the mean.
Trading Signals: Generates buy (long) and sell (short) signals based on predefined Z-score thresholds.
Visualization: Plots the spread along with buy and sell signals for visual analysis.

Dependencies
Python 3.x
Libraries: pandas, yfinance, matplotlib
