# Principal Component Analysis: Gasoline NIR Spectra

This folder contains a Principal Component Analysis homework from the Advanced Statistics and Data Analysis course. The analysis uses near-infrared spectroscopy data to predict octane values of gasoline-like liquid samples.

## Research Questions

1. Can we fit a linear regression model using all NIR spectral variables?
2. Why is PCA useful when the number of predictors is larger than the number of observations?
3. How many principal components should be kept?
4. Can principal components be used as covariates in a linear regression model?
5. How can the octane value of a new sample be predicted?

## Files

- `gasoline-pca-nir-analysis.Rmd`: R Markdown file containing the full PCA and regression analysis
- `gasoline.rda`: dataset containing octane values and NIR spectra

## Methods Used

- Principal Component Analysis
- Scree plot
- Cumulative explained variance
- Dimensionality reduction
- Linear regression using principal component scores
- Model interpretation
- Prediction workflow for new samples

## Tools Used

- R
- dplyr
- factoextra
- prcomp
- lm

## Summary

The dataset contains 60 gasoline samples and 401 NIR spectral variables. Because the number of predictors is much larger than the number of observations, 
fitting a standard linear regression model using all variables is not appropriate. PCA is used to reduce the spectra to a smaller number of principal components.
The first five components explain approximately 98.3% of the total variance and are used in a linear regression model to predict octane. 
The resulting model explains about 98% of the variability in octane values.
