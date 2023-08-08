# Binomial Option Pricing Model

This is a notebook about the Binomial Options Pricing model. We formulate the model, give examples and explore the limiting behavior as the size of the interval becomes smaller. We demonstrate the relation with the Black-Scholes-Merton pricing model. The main reference is "Introduction to the Mathematics of Finance" by Steven Roman (2nd Edition, Springer, 2012). The sections of the notebook are as follows:

* Formulation. A mathematical description of the model, and the formulas for call and put option prices. A statement of the put-call parity formula.

* Implementation. The function `initial_price` computes the option prices based on the binomial formula, using the martingale probability (`martingale_prob`).

* Example. We demonstrate the binomial option pricing formula in action with an example (Example 6.1 in [Roman]). We include plots of the prices for different strikes. 

* Limit. Plots showing the behavior of the model as the number of intervals increases (equivalently, as the interval size decreases). The time to expiry does not change.

* Black-Scholes-Merton. We implement the Black-Scholes-Merton pricing formula (`black-scholes`) and compare it to the binomial option pricing models. The later limits to the former as the interval size decreases (`compare_models`). 

