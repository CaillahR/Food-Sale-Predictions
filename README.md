# **Overview:**
---
This model provides the data of all food items in certain grocery stores in India, to predict which items will sell. It includes a data dicitonary to easily explain to the reader what each column represents; Exploratory and Explanatory visuals displaying correlations, utilizing scatterplots, and box plots.


# Food Sale Predictions
## Highest and Reccommendation of increase sales

**Author**: Caillah Reed

### Business problem:

Which stores have the highest sales and what needs to be done to increase, or keep steady, sales?


### Data:
This dataset has the summary of items(Weight, Fat Content, Visibility, Type, and MRP) and the outlet (Location Type, Outlet Type)
- Cleaned the data
- dropped columns that do not pertain to the outlet sales, giving us a cleaner (more focused) view

## Results

#### Visual 1 Title
![sample pics/sales_over_the_EOY.png](https://raw.githubusercontent.com/CaillahR/Food-Sale-Predictions/main/sample%20pics/sales_over_the_EOY.png)

> This line plot displays the sales over the time of established outlets

#### Visual 2 Title
![sample pics/sales_vs_mrp.png](https://raw.githubusercontent.com/CaillahR/Food-Sale-Predictions/main/sample%20pics/sales_vs_mrp.png)
> This scatter plot displays the sales with their corresponding MRP
## Model

-Regression Tree is the optimum model for this data with a lesser error calculation and a higher fit percentage

-R2(models' predictions): 59% on our testing dataset; RMSE(error margin): 1,057.44 error margin

This Model will explain the data set very well by reducing large errors in predicting which stores will have the highest sales and what needs to be done to increase, or keep steady, sales.

## Recommendations:

Reccomendation: Make products that are not selling, higher in value. This may spark a change in sales.

Reccomendation : Find out why sales were shot down in between 1995-2000's and what was done differently to bring them back up. Recreate that situation and you may be able to keep sales steady again.

## Limitations & Next Steps

Limitations of this model is that predictions are off by 41% and correlation does not equal causation. The data may be showing a pattern between two items but it does not necessarily mean one caused the other to happen.


### For further information


For any additional questions, please contact **caillahreed@yahoo.com**
