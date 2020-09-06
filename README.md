# Risk-Factors-Identification-using-SAS
## Objective
To identify potential risk factors that may have an association with low birth weight.

## Methods and Implementation
1. Data preparation and feature engineering
2. Conduct demographic analysis to see whether the distribution of the variables are different in two groups and prefilter important features.
- t-test; Wilcoxon rank-sum test
- Chi-square test
3. Univariate analysis using logistic regression
- Apply Deviance, Wald test and AIC to preliminarily select the variables.
4. Multivariate analysis using logistic regression
- Apply Deviance, Wald test and AIC to preliminarily select the variables.
5. Model checking: to evaluate the goodness-of-fit of the model and to identify the outliers.
- Hosmer-Lemeshow goodness of fit test
- Deviance goodness of fit test

## Conclusion
The history of premature labor, the history of hypotension, the presence of  uterine irritability are risk factors that increase the odds of delivering a low birth weight baby in each of the model.
Deviance works best, because it covers the fewest variables and all of them are significant with a smallest deviance. 


