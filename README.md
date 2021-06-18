# Exotic-Options-Pricing

Before pricing exotic options, Vanilla Eurpoean Options should be priced using the Black Scholes Formula and the result should be validated with Monte Carlo Simulations. In doing so, volatliy can be taken as a user input. 

After this, the General Brownian Motion Equation can be used to price the path dependant exotic options(again with vol as input) using Monte Carlo Simulations. In this project, I price call and put options of the barrier options-Knock In(Up&In, Down&In) and Knock Out(Up&Out,Down&Out). First, I modelled it under the assumtion that vol was provided directly.

After this, vol was iteratively looked up from the Bloomberg Market Data corresponding to Risk Reversal, Butterfly and ATMF options for various tenors.

