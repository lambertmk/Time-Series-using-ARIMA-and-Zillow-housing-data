
# Time Series using ARIMA and Zillow housing data

## Important Links

mod_4_starter_notebook.ipynb: jupyter notebook used for this project

github link: https://github.com/lambertmk/Module-4-Project

google slides link: https://docs.google.com/presentation/d/1qohvqViuZPv_MSQaawtA_QAwLGcn0NWcv8Z7iPLUV6s/edit#slide=id.g7673b104bc_0_31

blog post link: https://medium.com/@ml_85095/forecasting-housing-prices-from-zillow-4b1f234da722

map of five zip codes analyzed: https://www.zeemaps.com/map?group=3776529&add=1#


## Introduction
For the module 4 project, I was tasked with identifying the "best" zip codes for a fictional real estate firm to invest in. This could be in the region of my choice, or nationally. I focused on the Metro Detroit area, since it's an area that I know well.

## Overview
I first calculated the ROI and coefficient of variation for each zip's values. This allowed me to select the zip codes with the highest ROI within a determined level of risk.

For those five zips, I next ran an augmented Dickey-Fuller test to look for stationarity.

I next ran an ARIMA function to determine the best hyperparameters for our forecasting model. Each zip code was then forecast for the next 24 months, a reasonably short time frame given that this is for an investment firm rather than serious homebuyers. 

Each zip was then analyzed for potential returns.
