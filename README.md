### Spearman-s-Rank-Correlation-Test
Heteroscedasticity can also be detected using Spearman's Rank Correlation Test.
The Spearman's Rank Correlation Test serves the purpose of detecting heteroscedasticity within the data.
A significant test is conducted to identify the presence of heteroscedasticity, where heteroscedasticity is confirmed if the p-value is lower than the predetermined significance level, alpha.
To perform this function follow step-by step procedure
```R
Go to "Stat"
Go to "Regression"
Go to "Regression"
Go to "Fit Regression Model"
Put "y" in response
Put "x" in continious predictor
Go to "Storage"
Click option "Residuals"
click "OK"
Write "absresi" in next column
Go to "Calc"
Go to "Calculator"
Put "absresi" in Store result in variable
Go to function search "Absolute value"
Click "Absolute value"
Abs appears in Expression
Click "RESI"
Click "OK"
Go to "Stat"
Go to "Basic Statistics"
Go to "Correlation"
Put "absresi" and "x" in variable
Click method and change it to "Spearman rho"
Click "OK"
Write "t" in next column
Go to "Calc"
Go to "Calculator"
Put "t" in Store result in variable
According to this data:
Write "((0.333)*SQRT(10-2))/(SQRT(1-(0.333*0.333)))" in Expression
According to formula:
t=(rs*sqrt(n-2))/(sqrt(1-(rs*rs)))
Where, rs is spearman rank correlation value 
Click "OK"
Write "df" in next column
Go to "Calc"
Go to "Calculator"
Put "df" in Store result in variable
Write "10-2" in Expression
Click "OK"
```
Here alpha is "0.10"
Now check p-value
According to this data, t-value is 0.998, which lie is in one tail test between 0.2 and 0.15 with df=8, add 0.2+0.15, then divided by 2, i.e., p-value is 0.17
According to given data in file p-value is greater than alpha.
So, it effected insignificantly and have homocedasticity at 10% level of significance.
If p-value is less then alpha. Then it effected significantly and have heteroscedasticity at 10% level of significance.

![spearman t table](https://github.com/UMMY87/Spearman-s-Rank-Correlation-Test/assets/117314436/f8fc6bfa-c84e-4378-ab3f-d19069f21705)
