# Generalized Linear Models: Titanic Survival Analysis

This folder contains a Generalized Linear Models homework from the Advanced Statistics and Data Analysis course. The analysis uses Titanic passenger data to study survival probability as a function of passenger type and travel class.

## Research Questions

1. Which passenger group had the highest probability of surviving?
2. Which passenger group experienced the highest mortality?
3. Do the parameter estimates support the statement that preference was given to women and children?
4. Was preference given more to children or more to women?
5. Did passenger class affect survival?
6. Were second and third class passengers treated differently with respect to survival?

## Files

- `titanic-glm-survival-analysis.Rmd`: R Markdown file containing the full analysis
- `titanic.rda`: Titanic dataset used for the analysis

## Methods Used

- Logistic regression
- Generalized linear models with binomial family
- Predicted survival probabilities
- Odds ratio interpretation
- Likelihood ratio test
- Linear hypothesis testing
- Model comparison using analysis of deviance

## Tools Used

- R
- dplyr
- tidyr
- car
- glm
- binomial logistic regression

## Summary

The analysis fits a logistic regression model to estimate the probability of survival on the Titanic based 
on passenger type and class. The results show that women and children had substantially higher survival
probabilities than men. However, passenger class also strongly affected survival: second and third class 
passengers had lower survival odds than first class passengers, and third class passengers had significantly worse survival 
outcomes than second class passengers.
