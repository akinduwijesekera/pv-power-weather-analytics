# Photovoltaic Power Prediction Based on Weather Data

UCL ELEC0033 Internet of Things — Data Analytics Report (individual)

## Overview

A data analytics pipeline applied to weather data from multiple Danish
cities and Perth, Australia. The dataset was cleaned using complete case
analysis and outlier detection based on z-scores, followed by interpolation
to correct anomalous values. Descriptive statistics and correlation
analysis were used to identify key feature relationships, including the
influence of cloud cover on rain probability. A multivariate linear
regression model was developed to predict photovoltaic (PV) production,
achieving an R\` of 0.74. The results highlight the predictive importance
of temperature, humidity, and solar irradiance for renewable energy
forecasting.

See \`Data_Analysis_report_22008430.pdf\` for the full write-up.

## Data

\`Coursework_weather_data.ipynb\` expects two files in the same directory,
which aren't tracked in this repo (data, not code):

- \`weather-denmark-resampled.pkl\` — weather observations from Aalborg,
  Aarhus, Esbjerg, Odense and Roskilde
- \`df_perth.pkl\` — weather data for Perth, Australia, used for the PV
  production regression

These were provided as part of the ELEC0033 coursework resources.
