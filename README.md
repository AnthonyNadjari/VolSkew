Option Vol Skew - SPX

# Computation of the Volatility Skew for 1 year and 3 months call options on SPX

The file aims at computing a vol skew curve for options of the S&P500.

* **1Y and 3M maturities**: we use Bloomberg-available data to get the prices of call options for these maturities (strike date 18 February 2022, spot = 4380.26)

* **Method used**: We download prices for 50 to 100 strikes. We then use Newton-Raphson's method on each strike to get an implied volatility approximation.
