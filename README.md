# Option-Pricing-Models

This repository contains Python implementations of option pricing models using binomial and trinomial trees.

## Project Description

This project includes
- Option Base Class A base class for financial options, including attributes like initial stock price, strike price, interest rate, time to maturity, number of steps, and other parameters.
- Binomial Tree Model An implementation of the binomial tree method for option pricing.
- Trinomial Tree Model An implementation of the trinomial tree method for option pricing.

## File Structure

- `option.ipynb` Contains the base `Option` class.
- `binomialpricing.ipynb` Contains the `BinomialTree` class, which inherits from the `Option` class and implements the binomial tree model.
- `trinomialpricing.ipynb` Contains the `TrinomialTree` class, which inherits from the `BinomialTree` class and implements the trinomial tree model.
