# High-Dimensional Regression: Ridge and Lasso

This folder contains a high-dimensional regression homework from the Advanced Statistics and Data Analysis course. The analysis uses the Boston housing dataset to predict median housing value using ridge and lasso regression.

## Research Questions

1. How can ridge regression be used to predict median housing value?
2. How does ridge shrink regression coefficients as lambda increases?
3. How can cross-validation be used to select lambda?
4. How does lasso regression differ from ridge regression?
5. Which model gives better prediction performance on the test set?
6. How does lasso help with variable selection?

## Files

- `boston-ridge-lasso-regression-analysis.Rmd`: R Markdown file containing the full ridge and lasso analysis

## Dataset

The dataset is loaded directly from the `MASS` package using:

```r
data("Boston")
