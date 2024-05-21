# Weather Variability and Precipitation in Lake Tahoe: El Niño and La Niña Study

## By: Garrick Hague

## Objective:

1. Clean and preprocess datasets for analysis.
2. Create anomalies dataset using sea surface temperature and precipitation data.
3. Determine sea surface location with highest correlation to Lake Tahoe Region.
4. Identify best linear regression model for predicting Lake Tahoe precipitation.

## Background:

This project focuses on the Southern Oscillation, a key region in the equatorial Pacific Ocean, crucial for predicting weather patterns across the United States. Variations in sea surface temperatures here influence atmospheric pressure, driving weather patterns globally. This study investigates the impact of Southern Oscillation teleconnections on Lake Tahoe's unique weather patterns.

## Conclusion:

This analysis involved rigorous data cleaning and preprocessing. Precipitation data was refined for Lake Tahoe region, and sea surface data aligned with precipitation timeframe. Datasets were resampled into quarters and grouped into seasons. Anomalies were generated based on a 30-year time mean from 1982 to 2012.

Various ordinary least squares regression models were employed, including those considering maximum correlation location, El Niño/La Niña periods, and specific El Niño or La Niña ranges. While the max correlation model showed the most promise, none yielded high R^2 values, and p-values indicated lack of statistical significance. However, the absence of serial correlation was noted.

To enhance the study's robustness, longer precipitation data and exploration of models across different viewing windows, such as shifting to the west side of Sierra Mountains, could provide valuable insights.

## Thank you for your time
