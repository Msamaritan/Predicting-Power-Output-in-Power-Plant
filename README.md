# Predicting-Power-Output-in-Power-Plant

## Problem Description
   The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.
      
   A combined cycle power plant (CCPP) is composed of gas turbines (GT), steam turbines (ST) and heat recovery steam generators. In a CCPP, the electricity is generated by gas and steam turbines, which are combined in one cycle, and is transferred from one turbine to another. While the Vacuum is colected from and has effect on the Steam Turbine, he other three of the ambient variables effect the GT performance.
   

## Solution Approach 
   We can use normal Multiple Regression to solve this problem, but doesn't it seems a bit older, boring naive approach to solve Regression problems, so we are going to use Deep Neural Networks to solve this problem with higher accuracy. 10000 observations is a smaller dataset for neural networks, maybe with fine tuning the machine learning algorithms you will get higher accuracy for this problem but the neural networks will always stay at its apex when we have larger data.
   
## We are going to create ARTIFICAL NEURAL NETWORKS (ANN) for this solution.
   
