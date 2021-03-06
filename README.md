# HousePricePrediction: 

## Project Overview
* Created a tool that estimates the house price to support the decision of buying a house. Is the price is too high or it is worth to buy.
* Evaluate Linear, Lasso, Ridge and Random Forest Regression Models </br>
** Optimiue the models with Grid Search CV

## Code and Resources Used
* **Programming Language:** Python
* **Packages:** pandas, numpy, matplotlib, seaborn, missingno, sklearn
* **Data:** [Kaggle Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## EDA
* **Shape of the data:** 2919, 79
* **Target:** Min: 34.900, Max: 755.000

![](/images/TargetDistribution) </br>
(pink: Mean, red: Median)

![](/images/TargetBoxPlot)

* **NaN-Values** </br>
![](/images/DataFrameNaN.png)
![](/images/PercentageNaN)

* **Correlation of Features and Target:** </br>
![](/images/Heatmap)

## Data Preparation
### Target Scaling
![](/images/ScalingTarget)


## Results
![](/images/Results.png)



