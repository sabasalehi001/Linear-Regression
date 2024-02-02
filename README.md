# Simple Linear Regression Exercise

## Overview

This repository features Python code for a straightforward linear regression task using real estate data. The primary goal is to predict real estate prices based on property size. The dataset, 'real_estate_price_size.csv,' is included.

## Instructions

1. **Import Libraries:** Utilize necessary Python libraries:

   - NumPy
   - Pandas
   - Matplotlib
   - Statsmodels
   - Seaborn

2. **Load Dataset:** Read the real estate dataset into a Pandas DataFrame.

3. **Explore Data:** Obtain summary statistics to understand the dataset better.

4. **Declare Variables:** Identify the dependent ('price') and independent ('size') variables.

5. **Visualize Data:** Create a scatter plot to visually represent the relationship between size and price.

6. **Build Regression Model:** Use the Statsmodels library to create a linear regression model.

7. **Plot Regression Line:** Visualize the regression line on the scatter plot, offering insights into the size-price relationship.

## Regression Results

The regression model yields an R-squared value of 0.745, indicating a good fit. The coefficient for 'size' is 223.1787, implying that for each unit increase in size, the price is predicted to increase by 223.1787 units. Detailed information can be found in the regression results.

Note: Be mindful of assumptions and notes provided in the regression results.
