# Monte Carlo GBM Industry Returns Simulations

1. I used the log return values instead of real return as the log returns are normally distributed. This statistical property allows me to use a GBM model to simulate future returns.

2. I used a Geometric Brownian Motion model with two terms related to the expected return and standard deviation of each industry. The model was used to simulate future industry returns over a 5 year time horizon.

3. The GBM model is a Markov process, meaning "tomorrows” industry return is only dependant on “today’s” industry value and no other time point in the past. It is important to note that the simulated value is consistent with the weak form of the efficient market hypothesis, which assumes past price information has already been incorporated. Specifically, it assumes that price momentum does not exist.

3. To display these simulated returns in a more direct manner I assumed a €100 investment in each industry on the 30th September 2019. The valuations are calculated using our simulated log returns for each time period.

# Key Advantages of Geometric Brownian Motion (GBM)

•	The expected returns of GBM model are independent of the actual value of the industry which agrees with what we would expect in reality.
•	A GBM process only assumes positive values which fits as industry values can’t be negative.
•	A GBM process shows the same kind of random effects in its paths that we see in real returns.

