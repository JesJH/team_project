Linear Regression Model

1.	Overall transaction value by country

OLS Regression Results                            
==============================================================================
Dep. Variable:           Total_Amount   R-squared:                       0.000
Model:                            OLS   Adj. R-squared:                 -0.000
Method:                 Least Squares   F-statistic:                    0.7587
Date:                Sat, 22 Jun 2024   Prob (F-statistic):              0.552
Time:                        00:27:54   Log-Likelihood:            -2.4973e+06
No. Observations:              295617   AIC:                         4.995e+06
Df Residuals:                  295612   BIC:                         4.995e+06
Df Model:                           4                                         
Covariance Type:            nonrobust                                         
=====================================================================================
                        coef    std err          t      P>|t|      [0.025      0.975]
-------------------------------------------------------------------------------------
const             -3.956e+14   7.44e+14     -0.532      0.595   -1.85e+15    1.06e+15
Country_Australia  3.956e+14   7.44e+14      0.532      0.595   -1.06e+15    1.85e+15
Country_Canada     3.956e+14   7.44e+14      0.532      0.595   -1.06e+15    1.85e+15
Country_Germany    3.956e+14   7.44e+14      0.532      0.595   -1.06e+15    1.85e+15
Country_UK         3.956e+14   7.44e+14      0.532      0.595   -1.06e+15    1.85e+15
Country_USA        3.956e+14   7.44e+14      0.532      0.595   -1.06e+15    1.85e+15
==============================================================================
Omnibus:                    33870.038   Durbin-Watson:                   2.005
Prob(Omnibus):                  0.000   Jarque-Bera (JB):            47019.288
Skew:                           0.973   Prob(JB):                         0.00
Kurtosis:                       3.176   Cond. No.                     9.71e+14
...
Notes:
[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
[2] The smallest eigenvalue is 3.83e-25. This might indicate that there are
strong multicollinearity problems or that the design matrix is singular.

Analysis Results:

As all P-value is extremely large, we can know that Country is not statistically significant to purchase amount, which means the country that customers locate in is not associated with sales.


2.	Overall transaction value by income

OLS Regression Results                            
==============================================================================
Dep. Variable:           Total_Amount   R-squared:                       0.000
Model:                            OLS   Adj. R-squared:                  0.000
Method:                 Least Squares   F-statistic:                     1.065
Date:                Sat, 22 Jun 2024   Prob (F-statistic):              0.363
Time:                        00:28:00   Log-Likelihood:            -2.4973e+06
No. Observations:              295617   AIC:                         4.995e+06
Df Residuals:                  295613   BIC:                         4.995e+06
Df Model:                           3                                         
Covariance Type:            nonrobust                                         
==============================================================================
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
const       4.166e+14   3.84e+14      1.084      0.278   -3.37e+14    1.17e+15
High       -4.166e+14   3.84e+14     -1.084      0.278   -1.17e+15    3.37e+14
Low        -4.166e+14   3.84e+14     -1.084      0.278   -1.17e+15    3.37e+14
Medium     -4.166e+14   3.84e+14     -1.084      0.278   -1.17e+15    3.37e+14
==============================================================================
Omnibus:                    33870.986   Durbin-Watson:                   2.005
Prob(Omnibus):                  0.000   Jarque-Bera (JB):            47020.971
Skew:                           0.973   Prob(JB):                         0.00
Kurtosis:                       3.176   Cond. No.                     4.31e+14
==============================================================================

Notes:
[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
[2] The smallest eigenvalue is 2.16e-24. This might indicate that there are
strong multicollinearity problems or that the design matrix is singular.

Analysis Results:

As all P-value is extremely large, we can know that 'Income' is not statistically significant to purchase amount, which means the income level is not associated with sales.
