# Machine Learning Final Project: Weather Prediction
## Austin Vuong (aav304), Nathan Ly (ntl247)

### Formulation
Weather patterns have been disrupted all over the world. Even in this current year, our seasons are atypical.  Weather forecasts are only reliable for a few days into the future.  We wanted to analyze weather data to predict upcoming irregularities in general weather patterns so that we may be better prepared in the coming months.

### Approach
We gathered NYC data from the past 9 years from the National Oceanic and Atmospheric Administration.  This dataset includes one entry for each day, which had details on geographic location, altitude, daily high temperature, and daily low temperature.  Check the Jupyter Notebook file for the report.  We used a Time Series Model to generate the calculated average of the daily Hi/Low temperatures of each month/year/day.  Simple Linear Regression was not practical because weather changes in cycles.  A Simple Linear Regression line would show a constant increase/decrease in temperature.

### Evaluation and Interpretation
It is difficult to test results for days in the future since they have not happened yet, but we did check to see if previous days throughout the years were close to the calculated values.  From our testing, about 60% of the predicted temperatures were within 20% of the actual temperatures.  One of the main shortcomings we encountered was a lack of data.  The data gathered was not as detailed as we would have liked because it only included latitude/longitude, elevation, date, daily high temperature, and daily low temperature.  Details such as humidity and precipitation would have been useful to make more detailed and accurate predictions about the weather.  We would also like to be more accurate, since only 60% of our testing was successful.
