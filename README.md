# Dummies and VIF - Exercise Solution

This repository contains my solution to an exercise on creating dummy variables and calculating Variance Inflation Factor (VIF) to evaluate multicollinearity in a dataset. This is part of my data science learning journey on Udemy, where I explore advanced techniques in regression analysis and feature engineering.

---

## About the Exercise

### Dataset:
The dataset used in this exercise is a real estate dataset, `real_estate_price_size_year.csv`, which includes:
- **Dependent Variable**: `price` (property price).
- **Independent Variables**:
  - `size` (size of the property in square feet),
  - `year` (construction year),
  - `category` (a categorical variable requiring dummy encoding).

### Objectives:
1. **Create Dummy Variables**:
   - Convert the `category` variable into dummy variables to use in regression analysis.
2. **Calculate VIF**:
   - Evaluate multicollinearity among the independent variables using Variance Inflation Factor (VIF).
3. **Perform Regression Analysis**:
   - Use the processed data to fit a multiple linear regression model.
4. **Interpret Results**:
   - Analyze the model coefficients and multicollinearity metrics.

---

## Tools and Libraries Used

- **`numpy`**: For numerical operations.
- **`pandas`**: For data preprocessing and dummy variable creation.
- **`statsmodels`**: For regression analysis and VIF calculation.
- **`matplotlib`**: For data visualization.

---

## Key Highlights of the Exercise

1. **Dummy Variable Creation**:
   - Transformed the categorical `category` variable into dummy/indicator variables.

2. **VIF Calculation**:
   - Evaluated the degree of multicollinearity among the predictors.
   - Identified variables that might need removal or adjustment.

3. **Regression Model**:
   - Built a multiple linear regression model and interpreted the results.

### Sample Output:
Here’s an example of VIF results:

| Variable | VIF Value |
|----------|-----------|
| Size     | 2.35      |
| Year     | 3.02      |
| Category_A | 4.87    |
| Category_B | 5.12    |

---

