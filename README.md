# Ames Housing Price Analysis

This project analyzes housing prices using the Ames Housing dataset. The goal is to understand which features most strongly influence home prices and to explore how multiple factors interact to affect value.

## Overview

The analysis focuses on key housing features such as living area, overall quality, and basement size. Relationships between these variables and sale price were examined using visualization and correlation. A simple linear regression model was also built to explore how these features can be used to predict housing prices.

## Key Findings

- **Living area (Gr Liv Area)** has a strong positive relationship with sale price. Larger homes generally sell for higher prices.
- **Overall quality (Overall Qual)** is the most influential variable, creating clear price tiers across homes.
- **Year Built** shows a weaker relationship with price, indicating that age alone does not determine value.
- **Basement size (Total Bsmt SF)** provides only a small improvement in prediction, as it overlaps with overall living space.
- A simple regression model using size and quality provides reasonable estimates but still has noticeable error.
- Additional variables such as location and renovations are likely needed to improve prediction accuracy.

## Methods

- Data cleaning and feature selection using Pandas
- Visualization using Matplotlib (scatter plots)
- Correlation analysis to measure strength of relationships
- Linear regression modeling using Scikit-learn

## Tools Used

- Python
- Pandas
- Matplotlib
- Scikit-learn

## Conclusion

This project demonstrates that housing prices are primarily driven by size and quality, but cannot be fully explained without additional factors such as location and renovation history. While a simple model can capture general trends, more complex modeling and additional features would be required for higher accuracy.
