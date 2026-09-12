# STAT 231 - Applied Linear Regression Files (SPRING 2027)



### Assignments

| File | Topic |
|---|---|
| `assignment/Assignment-1` | R basics - random number generation, vectors, subsetting, scatter plots, adding lines & legends |
| `assignment/Assignment-2` | Simple linear regression - fitting SLR, R², hypothesis test on slope, 95% CI on slope and mean response, ANOVA table |
| `assignment/Assignment-3` | Multiple linear regression. - scatterplots & correlations, model selection (best subsets + stepwise + AIC), manual matrix computation, residual analysis (standardized, studentized, R-student, PRESS), outliers |
| `assignment/Assignment-4` | Factors & interactions - `mtcars` dataset, weight vs mpg by engine type, full model with two-way interactions, stepwise selection, diagnostics, interpretation |

### Worksheets

| File | Topic |
|---|---|
| `worksheets/Worksheet-1` | Patient satisfaction data - scatterplots & correlations, all-subsets model comparison (R² / adjusted R²), residual diagnostics, outlier detection & removal |
| `worksheets/Worksheet-2` | Polynomial regression - linear vs quadratic models, normality of residuals (Q-Q + Shapiro-Wilk), residual/studentized/R-student plots, outlier identification |
| `worksheets/Worksheet-3` | Transformations - `cars` dataset, log transformation to improve linearity, comparing linear/quadratic/log-log models, constant variance check, adjusted R² comparison |
| `worksheets/Worksheet-4` | Multicollinearity - `Boston` dataset, polynomial terms, VIF, centered predictors to fix collinearity, R² improvement |

### Course Project

**"Analysis of Car Price and Economy in Qatar"** (`course-project/`)
- Multiple linear regression on the `qatarcars` dataset
- **Economy model:** `log(economy) ~ horsepower + mass + enginetype` (R² = 0.602)
- **Price model:** `log(price) ~ horsepower` (R² = 0.862)
- Includes data cleaning, missing value handling (structural missingness for EVs), stepwise selection, diagnostics, and a **Bayesian** comparison using `brms` (credible vs predictive bands)


