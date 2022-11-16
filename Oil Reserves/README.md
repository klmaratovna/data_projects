# Description: Selecting a location for the well.
# Task:
Given the data of 3 regions, it is necessary to highlight the most promising region with the lowest risk of loss.
Building ML models for 3 regions, check forecasting with RMSE metric and find the best option, profit and risk. 
Apply bootstrap technique for normal distribution.

## Research objectives:

1. Examine input data,
2. Split data into training, validation and test sets,
3. Calculate sufficient and breakeven volume of raw materials given the input data,
4. Calculate profit based on predicted data,
5. Calculate risks and profit for each region.

## Data:

1. Target feature:

product - the volume of reserves in the well (thousand barrels).

2. Features:

id - unique identifier of the well;
f0, f1, f2 - three signs of points (it doesn't matter what they mean, but the signs themselves are significant);
