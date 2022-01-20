# PyBer_Analysis
## Overview

### This analysis seeks to provide insights into ride accessibility and affordability for PyBer, a Python-based ride-sharing app company. Our goal is to perform exploratory data analysis on a large dataset to determine the relationship between the type of city, the number of drivers and riders, and the percentage of total fares, riders, and drivers by type of city. To achieve this goal, We would create several visualizations, write python scripts using pandas library and Matplotlib to create various charts. In the end, we hope to use the analysis and visualizations we produce to improve access to ride-sharing services and determine affordability for underserved neighborhoods.

### After creating initial results, our analysis moves to a second phase where we make a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we would create a multiple-line graph that shows the total weekly fares for each city type. Finally, we would summarize how the data differs by city type and how decision-makers can use those differences at PyBer to answer questions around ride accessibility and affordability.

# Results

### Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, we get the total number of rides, total number of drivers, and the total fares for each city type. We Then, calculated the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, and then formatted the columns to obtain the following summary result.

###  Ride-Sharing Summary DataFrame

### PyBer_summary_DataFrame

# ![image](https://user-images.githubusercontent.com/85313508/150419123-b5571de9-3e14-4c19-b28e-d9db5d0baaa5.png)


### Using the object-oriented interface method and the df.plot() method, as well as the Matplotlib "fivethirtyeight" graph style, we graphed the resampled DataFrame from the previous result to obtain to fares for the weekly bins in the following graph.

### Line Chart Showing Total Fares by City Type

# ![image](https://user-images.githubusercontent.com/85313508/150419267-ef2ba563-1909-4b2c-8a25-edcb0ba5d469.png)

# Summary 

### Another recommendation is to find the sweet spot between average fare per ride (cost to the rider) and average fare per driver (revenue to the driver). A way to achieve the optimal solution to the optimization problem is to maintain a minimum threshold of driver count across all city types while increasing the number of riders. An increasing number of riders would reduce mean fares and lead to a multiplier effect on ride count. Similarly, maintaining a driver count threshold across different city types could result in fare per driver upper and lower boundaries that are not too far apart.

### While the Average fare per driver is highest for rural cities ($55.49) with a mean ride count of 7, that amount pales compared to the $16 and average round count of 24 in urban cities. 

### Answers to questions like these can help illuminate the disparities between the fares and driver count in rural and urban cities and provide concrete steps to making rides affordable and accessible across all city types.
