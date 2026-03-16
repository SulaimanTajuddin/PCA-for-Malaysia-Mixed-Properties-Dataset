# Random Forest Regressor & Principal Component Analysis for Malaysia Mixed Properties Dataset
Applying Random Forest Regressor & Principle Component Analysis (PCA) towards Malaysia Mixed Properties Dataset to analyze the practicality of both method

Imagine you have many engineers (called decision trees) trying to estimate something—for example:

Predicting boiler efficiency
Forecasting pump performance
Estimating energy consumption

Each engineer gives their own estimate.
Random Forest Regressor is like taking the average of all their answers.
Because you don’t depend on just one engineer, the result is more stable, more accurate, and less sensitive to mistakes.

So:

👉 Random Forest = many small decision trees working together as a team

👉 Regressor = used to predict numbers (continuous values)

PCA is a mathematical technique used to reduce the number of variables in a dataset while keeping most of the important information.
Think of it as compressing data without losing much meaning—like turning a big, detailed photo into a smaller file that still looks almost the same.

Imagine you have 10 sensors in a factory measuring different aspects of a process (flow rates, temperatures, pressures, chemical concentrations, etc.).
Often, these sensors are related—if temperature goes up, maybe pressure also goes up.

So instead of analyzing all 10 sensors separately, PCA tries to:

👉 Find the underlying patterns.
It finds the main “directions” in which the data varies the most.

👉 Combine related variables.
It merges them into new variables called principal components.

👉 Keep only the most important components

The first few components explain most of the variation—so you end up with a simpler dataset.
