# Monte-Carlo-Simulation
Usage of Monte Carlo Simulation to Optimise Portfolio to maximise an investor's max returns off a given investment amount vested among various assets.

# About the project 
I forecasted stock prices using the Monte Carlo simulation. I used this data to predict the weights associated with each associated for getting maximal returns at minimal risk. Moreover I generated the optimum portfolio using various risk-return measures like sharpe ratio, and discussed various normality quantification norms like Q-Q plot etc. I also analysed the relationship between various assets by correlation and covariance matrix that would help the investor in finding the optimal portfolio based on a certain risk-free rate.

![image](https://github.com/beingamanforever/Monte-Carlo-Simulation/assets/121532863/efe41626-39c0-4113-9905-2c40e556040c)

# Important Links
> [!IMPORTANT]
> Do refer the following links for the complete overview and documentation of the project
Medium Documentation - [Link](https://medium.com/@beingamanforever/portfolio-optimisation-using-monte-carlo-simulation-25d88003782e)
, Alternate approach via Quantum Computing methods - [Medium Link](https://medium.com/@beingamanforever/quantum-computing-for-portfolio-optimization-58c8c93cd420) , [Github Repository Link](https://github.com/beingamanforever/MCS-using-Quantum-Computing)

# Further Recommendations
> [!TIP]
> Some further recommendations upon which the model may be extended to gather more insights.
1. Incorporate measures of normalities like Q-Q plot (used above), Box Plots, Kolmogonov Smirmov Test to quantify normality, this would help in visualizing the quantification of the normality of the data.
2. Usage of the Exponential moving average(EMA) the calculation for EMA emphasizes the recent data points. EMA responds more quickly to changing prices than the Simple Moving Average(SMA).
3. Effect of number of days taken into account during the calculation of moving average and how it affects the smoothening.
4. Use other Risk-Return measures such as the Sortino Ratio, M2 Ratio, Calmar Ratio and calibrate their differences, and use the most suitable one according to the scenario.
5. Usage of Geometric Brownian Motion(GBM) instead of Arithmetic Brownian Motion(ABM) for the generation of randomized paths which would be fed into the Monte Carlo Simulation.
6. Observe how changing the risk factor affects the optimal portfolio.

![image](https://github.com/beingamanforever/Monte-Carlo-Simulation/assets/121532863/e7389c35-5908-44c5-89fb-ac143575993c)


# References used
1. Investopedia
2. QuantPy youtube channel
3. Blogs on Medium
4. MIT lectures on Monte Carlo Simulation [here](https://www.youtube.com/watch?v=OgO1gpXSUzU)
