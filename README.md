# Taiwan vs Ohio Weather
A project to determine which months have similar weather conditions between the two locations.

## Data 
The dataset consists of monthly averages for weather observations including temperature (mean/low/high), precipitation, humidity, dew point, wind speed, air pressure, and visibility. The data comes from [timeanddate.com](https://www.timeanddate.com/weather/).

## Methods
I used principal component analysis (PCA) to reduce the dimensionality of the data, and computed the Euclidean distances between pairs of months.
