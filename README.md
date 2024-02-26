# Natural Gas Storage Contract Pricing Tool 

## Introduction
Building upon the earlier work in forecasting natural-gas-prices-prediction project (https://github.com/muykhenglong/natural-gas-price-prediction), this project calculates the value of storage contracts for natural gas. The tool incorporates a variety of parameters, including injection and withdrawal dates, market prices, rates of gas flow, storage capacity, and associated costs, to provide a valuation of natural gas storage contracts.

## How It Works
The valuation tool operates by processing the following inputs:
* Injection Dates: The specific dates when natural gas is scheduled to be injected into storage.
* Withdrawal Dates: The specific dates when natural gas is scheduled to be withdrawn from storage.
* Injection/Withdrawal Rates: The rates at which gas can be injected into or withdrawn from storage.
* Maximum Storage Volume: The capacity limit for the storage facility, dictating the maximum volume of gas that can be held.
* Storage Costs: The costs associated with storing natural gas.

The function takes user inputs of the above variables, dynamically retrieves market prices for the specified injection and withdrawal dates from natural-gas-prices-prediction project, and return the contract value.
