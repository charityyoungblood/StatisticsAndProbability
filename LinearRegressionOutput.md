<!-- Reading and Interpreting Linear Regression Output --> 



## Example of our Linear Regression Output for Salary vs. Years of Experience

Call:
lm(formula = Salary ~ YearsExperience, data = sal)

Residuals:
    Min      1Q  Median      3Q     Max 
-7958.0 -4088.5  -459.9  3372.6 11448.0 

Coefficients:
                Estimate Std. Error t value Pr(>|t|)    
(Intercept)      25792.2     2273.1   11.35 5.51e-12 ***
YearsExperience   9450.0      378.8   24.95  < 2e-16 ***

Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 5788 on 28 degrees of freedom
Multiple R-squared:  0.957,	Adjusted R-squared:  0.9554 
F-statistic: 622.5 on 1 and 28 DF,  p-value: < 2.2e-16

## ###################################
For Linear Regression, we use the Sum of Squares of Residuals Formula: 
        SSres = SUM((yi - yi^)^2)

1. Intercept: these are the constant values from our