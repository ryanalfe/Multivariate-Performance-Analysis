# Multivariate Analysis of International Track Performance

## Overview

This project analyzes international women's running records across seven events using multivariate statistical methods in R.

The analysis explores whether performance across several race distances can be represented using a smaller number of underlying dimensions.

## Methods

The project uses:

- Principal Component Analysis (PCA)
- Factor Analysis
- Varimax rotation
- Covariance and correlation matrices
- Factor scores
- Multivariate outlier detection
- Data visualization

## Key Findings

The analysis identified two broad dimensions of athletic performance:

- Short-distance / sprint performance
- Longer-distance performance

Using standardized variables produced a clearer factor structure across events measured on different scales.

Potential multivariate outliers were also identified using factor scores.

## Technologies

- R
- R Markdown
- ggplot2
- Base R statistical functions

## Files

- `analysis.Rmd` — complete reproducible analysis
- `analysis.html` — rendered report
- `data/` — source datasets
- `figures/` — exported visualizations
