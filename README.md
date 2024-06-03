Objective: The primary aim of this project is to leverage real-time data from Polygon and PyCaret to conduct comprehensive analysis and prediction tasks on selected currency pairs, culminating in the implementation of a Long/Short (L/S) trading strategy.
Components:
Regression Analysis:
Utilization of ten base currency pairs (EURUSD, EURCHF, EURCAN, GBPEUR, GBPUSD, GBPCHF, GBPCAN, USDCHF, USDCAN, USDJPY) for regression modeling.
Incorporation of mean price, volume, and other statistical features derived from the base currency pairs.
Integration of correlations with EURUSD and BTC as supplementary features to enhance predictive capability.
Classification Task:
Classification of GBPUSD and USDJPY into forecastable (F), non-forecastable (N), and undefined (U) categories.
Utilization of PyCaret for efficient classification model development and evaluation.
Long/Short (L/S) Trading Strategy:
Application of a 20-point univariable time series regression to determine the slope for GBPUSD and USDJPY.
Selection of Long and Short currency pairs based on regression slope analysis.
Commencement of L/S trading at hour #5, with adjustments made for the USDJPY-to-GBPUSD ratio.
Repetition of L/S strategy at hours #6 and #7, with closure at hour #8.
Calculation of profit/loss (P/L) for each step of the L/S strategy using a standardized investment amount.
