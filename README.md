Rain in Australia: Using meteorlogical data to predict Rainfall
Introduction
Rainfall is a significant meteorological event that can affect local agriculture, transportation, water control, and more. It may be even more consequential for areas that experience relatively less rainfall than the rest of the world, such as cities and towns in Australia. The ability to accurately forecast rainfall could provide useful information to local government and industry, especially in a world feeling the effects of climate change.

The study will enable us to predict whether or not a location in Australia will experience rain tomorrow using the weather observation data. Given a set of features, we want to predict the target variable RainTomorrow as, 1 which shows either it will rain the next day or 0 which shows it will not rain the next day.

Technology/Datasets
For this study, we utilized the following Python libraries and datasets.

Pandas
Requests
Seaborn
Matplotlib
Scikit-learn
Warnings
SciPy
Rain in Australia
Dataset Description
The dataset has 23 features with 145460 observations. The features in the dataset are as follows:

Date: The date of observation.
Location: The location of the weather station where the observation was recorded.
MinTemp: The minimum temperature in degrees celsius.
MaxTemp: The maximum temperature in degrees celsius.
rainfall: The amount of rainfall recorded for the day in mm.
Evaporation: The pan evaporation (mm) in the 24 hours to 9am.
Sunshine: The number of hours of bright sunshine in the day.
WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight.
WindGustSpeed: Speed (km/h) of the strongest wind gust in the 24 hours to midnight.
WindDir9am: Direction of the wind at 9am.
WindDir3pm: Direction of the wind at 3pm.
WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am.
WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3pm.
Humidity9am: Humidity (percent) at 9am.
Humidity3pm: Humidity (percent) at 3pm.
Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am.
Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm.
Cloud9am: Fraction of sky obscured by cloud at 9am.
Cloud3pm: TFraction of sky obscured by cloud (in "oktas": eighths) at 3pm.
Temp9am: Temperature (degrees C) at 9am.
Temp3pm: Temperature (degrees C) at 3pm.
RainToday: Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0.
RainTomorrow: Yes if the rain for that day was 1mm or more, otherwise No.
