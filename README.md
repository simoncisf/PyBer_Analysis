# PyBer_Analysis

## Project Overview

This project is an analysis of ridesharing data on Python. V. Isualize, the CEO of the company, has asked us to use a dataset containing data on ridership for numerous cities to come up with business recommendations for addressing any disparities between the city types, namely urban, suburban, and rural. 

As seen in our Jupyter notebook, we make use of pandas, numpy, and matplotlib functions to process the data and create useful visualizations that allow us to understand and represent the different findings we obtain from this analysis.


## Results

# Rider Distribution

In the pie chart below, we can see how the total amount of PyBer rides in our dataset is distributed among the different types of cities. It is clear that urban cities correspond to the highest amount of rides. Suburban and rural cities amount to less than half of the total rides.

![total_rides](/Users/simon/Desktop/DS_Classwork/PyBer_Analysis/Analysis/total_rides.png)

# Driver Distribution

As for drivers, we see a similar distribution. There are many more drivers in urban cities than in suburban and tural cities, as seen in the pie chart below.

![total_drivers](/Users/simon/Desktop/DS_Classwork/PyBer_Analysis/Analysis/total_drivers.png)

# Fare Distribution

Lastly, we make a pie chart for the average fares by city type, as seen below. Rural cities correspond to the highest fares, followed by suburban then urban cities.

![total_fares](/Users/simon/Desktop/DS_Classwork/PyBer_Analysis/Analysis/total_fares.png)

# Average Fare Comparison

Before we move on to the comparison of fares between city type and between each month of the year, we create a table summarizing the data shown above and a couple more calculations that provide further insight into the data. We calculate the average fare per driver and average fare per rider for each city type. For both of these, we see an increasing trend as you go from urban to suburban to rural cities. In other words, PyBer fares are least expensive in urban cities, more in suburban cities and most expensive in rural cities.

![summary_table](/Users/simon/Desktop/DS_Classwork/PyBer_Analysis/Analysis/summary_table.png)

# Summary of Fares

Now that we have compared the fares for each city type, we create a pivot table with the dates as the index, so that we can compare the fares between each city type and how they change over time, for the four month period between January and April. We create a visualization of this pivot table as a line chart and show the results below. 

![PyBer_fare_summary](/Users/simon/Desktop/DS_Classwork/PyBer_Analysis/Analysis/PyBer_fare_summary.png)

# Conclusions

Based on our analysis, we can make the following conclusions:

* Rural cities are the most profitable for PyBer drivers, followed by suburban and then urban cities.
* There are disproportionately more drivers per ride in urban cities than in suburban and rural cities, indicating that there is a surplus of supply in urban cities and it is likely that drivers will start moving to suburban and rural cities.
* The previous conclusion goes hand in hand with this one, which is a prediction that demand for PyBer in rural cities will decrease due to the high cost per ride. This incentive would only be cancelled out if the number of drivers in rural areas increases enough such that it drives the prices down due to the increased supply. However, this might not happen because further investigation of PyBer data might reveal that the high cost of rides in rural areas is simply due to the longer travel distances.



