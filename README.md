# Source Code

# Modelling Individual Athletic Performance: A Bayesian Forecasting Framework for Elite Swimmers

## Overview
This repository contains the R code for my MSc Statistics dissertation at UCL,  which extends the Bayesian hierarchical model of Griffin et al. (2026) to generate probabilistic predictions of season best performance for elite 100 metres freestyle swimmers.

## Files
- `Womens_Data.Rmd`: Data processing, model fitting, prediction and evaluation for female athletes
- `Mens_Data.Rmd`: Data processing, model fitting, prediction and evaluation for male athletes
- `Updates.Rmd`: Additional analyses and adjustments made following supervisor feedback on the first draft

## Requirements
- R version 4.6.0
- The following R packages:
  - `dplyr`
  - `ggplot2`
  - `lubridate`
  - `coda`

## Model Fitting Code
The MCMC model fitting code (`fit_model.R`) was developed by the project supervisor,  Professor Jim Griffin, and is not included in this repository. It can be found on his website: https://jimegriffin.github.io/website/

## Data
The swimming performance data was provided from World Aquatics via the project supervisor.
