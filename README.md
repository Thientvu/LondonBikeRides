# London Bike Sharing Dataset
https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset

## Overview
This dataset provides historical data for bike sharing in London, powered by TfL Open Data. The information spans from January 1, 2015, to December 31, 2016, and is grouped by "Start time," representing the count of new bike shares per hour. The data includes weather information from freemeteo.com and data on bank holidays from https://www.gov.uk/bank-holidays.

## Metadata

- **timestamp**: Timestamp field for grouping the data.
- **cnt**: Count of new bike shares.
- **t1**: Real temperature in Celsius.
- **t2**: "Feels like" temperature in Celsius.
- **hum**: Humidity in percentage.
- **wind_speed**: Wind speed in km/h.
- **weather_code**: Category of the weather.
- **is_holiday**: Boolean field (1 for holiday, 0 for non-holiday).
- **is_weekend**: Boolean field (1 if the day is a weekend, 0 otherwise).
- **season**: Category field for meteorological seasons (0-spring; 1-summer; 2-fall; 3-winter).

**Weather Code** Category Description:
1. Clear: Mostly clear but may include haze/fog/patches of fog/fog in the vicinity.
2. Scattered Clouds/Few Clouds.
3. Broken Clouds.
4. Cloudy.
7. Rain/Light Rain Shower/Light Rain.
10. Rain with Thunderstorm.
26. Snowfall.
94. Freezing Fog.

## License
The dataset is provided under TfL's free transport data service, governed by the Open Government License 2.0 with specific amendments for Transport for London. Users are granted a worldwide, royalty-free, perpetual, non-exclusive license to use the information, with certain conditions such as attribution and adherence to traffic request limits.