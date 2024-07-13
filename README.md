# Exotic-Option-Pricing

Project Description

Objective

The goal of this project is to simulate the movement of the Dow Jones Industrial Average (DJIA) and the 3-month LIBOR rate using Geometric Brownian Motion (GBM) and the Vasicek model, respectively. Additionally, the project aims to price an exotic option based on the simulated data using Monte Carlo simulation.

Steps and Functions

	1.	Download Historical Data:
	•	Download DJIA and 3-month LIBOR data from Yahoo Finance using yfinance.
	•	Extract adjusted close prices for both datasets.
	2.	Data Preparation:
	•	Calculate log returns for the DJIA.
	•	Calculate log returns for the LIBOR rates.
	3.	Model Functions:
	•	Define the GBM model function for DJIA.
	•	Define the Vasicek model function for LIBOR rates.
	4.	Parameter Estimation:
	•	Use historical data to estimate the parameters of the GBM and Vasicek models using the Levenberg-Marquardt algorithm for non-linear least squares optimization.
	5.	Simulation:
	•	Simulate future paths for DJIA and LIBOR rates using the estimated parameters.
	•	Perform Monte Carlo simulation to price the exotic option with the defined payoff function.
	6.	Visualization:
	•	Plot the simulated versus actual DJIA and LIBOR rates to visualize the model’s performance.
