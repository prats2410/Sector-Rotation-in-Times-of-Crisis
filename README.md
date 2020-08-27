# A Sector Rotation Strategy That Beats the Market Handily, Especially During Crises


This is the github repository that contains the codes that have been used for the research paper: A Sector Rotation Strategy That Beats the Market Handily, Especially During Crises. 
It also contains the final results of these codes. 
The codes have been completely scripted in python.


In the folder named codes you will find the following:
- Calculating the returns and the summary statistics of ETFs: The code of this notebook calculates the summary statistics of the daily prices of the ETFs. It also calculates the daily closing returns and closing log returns of each ETF.
- Calculating the Equal-Weight Portfolio: The code of this notebook calculates the equal-weighted portfolio. An equal-weighted portfolio is one with equal investment in each security of the portfolio.
- Markov switching Models: This uses the hidden markov model and calculates the states of the ETFs as well as the states of VIX. The closing log returns of the ETFs have been feeded to this model for calculating the states of the ETFs where as the daily prices of VIX have been used to calculate the states of VIX.
- Portfolio calculations with transaction costs: Using the states of the ETFs as a signal and using the states of VIX as a signal, 6 different portfolio's have been calculated. Transaction costs have also been calculated in this notebook.
- Risk Free calculations: The US Treasury Bill daily price data has been used as the parameter to determine the risk free rate and this notebook shows how the risk free rate has been calculated.
