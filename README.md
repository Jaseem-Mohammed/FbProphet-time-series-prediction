# Overview

This project uses 10 years time series data of price for 1kg of onion in a particular market in India, and predicts the onion price for the next one year.
the data available has minor variations in price from the real market


## About the data
- Data is confined to Manjeri Market in Kerala, India
- Contains data from 24th November 2010 to 23rd November 2020
- price is indicated for 1kg of onion
- Data was gathered from [agmarknet.gov.in](https://agmarknet.gov.in/)
- Data is stored in the file 'agmarket_onion_price_2010-20.xlsx'

## Analysis
- Analysis is done using the python library 'fbprophet'
- Price is predicted for a periode of 1 year
- Analysis is done in the file 'fb_prophet_onion_price.ipynb'

## Forecast

- Forecasted data stored in the file 'onion_price_forecast.csv'

- This plot shows the price on y-axis and time on x-axis
- Shows price through the time periode in discussion.
![newplot1](https://github.com/Jaseem-Mohammed/Time-series-prediction-using-fbprophet/blob/main/images/newplot%20(1).png)

- Shows trent of price through different years as well as months.
![newplot2](https://github.com/Jaseem-Mohammed/Time-series-prediction-using-fbprophet/blob/main/images/newplot%20(2).png)

## Comparing prediction After 2 weeks

![p_v_a](https://github.com/Jaseem-Mohammed/Time-series-prediction-using-fbprophet/blob/main/images/Onion_p_v_a_2weeks.png)
