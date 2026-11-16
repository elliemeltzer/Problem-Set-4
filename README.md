# The Model That Fit Too Well

## Objective

I evaluated a store-revenue model to determine whether its high in-sample R-squared reflected reliable predictive performance.

## Methodology

- Simulated revenue data for 400 stores.
- Compared in-sample and held-out performance.
- Examined residuals, influential observations, and multicollinearity.
- Compared models of increasing complexity.
- Used nested cross-validation and a learning curve.
- Demonstrated how feature-selection leakage inflates validation results.

## Key Findings

The original model had an in-sample R-squared of 0.94 but systematically over-forecast large stores. A model with a floor-area spline performed best. Nested cross-validation estimated an MSE of about 3,183 and an RMSE of about 56. The results show that honest validation and appropriate model structure are more informative than a high in-sample R-squared.
