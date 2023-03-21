# Null-Hypothesis-testing-for-Recession’s-Effect-on-House-Prices-using-GDP-and-Homes-data
## Interpreting the results

T-Test: This is a test for the null hypothesis that 2 independent samples have identical average (expected) values. This test assumes that the populations have identical variances by default.

Null Hypothesis: It states that there is no effect or relationship between variables. The alternative of it states that effect or relationship exists.

After performing a hypothesis test, there are two possible outcomes:

	1. When p-value is lesser than or equal to significance level, you reject the null hypothesis. The data favoring the alternative hypothesis says your results are statistically significant.

	2. When p-value is greater than your significance level, you fail to reject the null hypothesis. Your results are not significant.

### The above p-values of the ttest_ind results:

From the above table we can clearly infer that the null hypothesis can be rejected and the hypothesis mentioned is proven to be True for 2019, but for 2008 the result is null hypothesis cannot be rejected. (Significance level, alpha = 0.05).

	We have performed different methods to fill the null values, as there were 4 members in the group each one worked on a different model to fill the null values and the last dataframe X shows the comparison of the ttest results which has given us better results with our models(Linear Regression 1 & 2) when compared to the in-built methods(SimpleImputer & KNNImputer).
