Interactive Black-Scholes Option Pricing Dashboard


This is a Streamlit-based interactive web application designed to calculate and visualize European option prices and Greeks using the Black–Scholes model.

Key Features

User inputs: Spot price, strike price, time to maturity, volatility, risk-free rate, and option type (Call/Put).

Outputs:

Option Price (Call and/or Put)

Greeks: Delta, Gamma, Vega, Theta, Rho

Visualizations:

Option price as a function of underlying price

Greeks plotted against underlying price

Interactive sliders and controls for real-time updates

Matplotlib charts embedded in Streamlit

Technology Stack

Python for calculations

NumPy and SciPy for numerical computation

Matplotlib for plotting

Streamlit for the interactive UI

Purpose

This dashboard serves as a learning and analysis tool for traders, finance students, and quants to understand:

How Black–Scholes prices change with different inputs

The sensitivity of an option’s price to changes in underlying parameters (Greeks)

The shape of pricing and Greek curves