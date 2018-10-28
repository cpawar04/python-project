# python-project
Bike rentals demand forecasting

Bike sharing market is growing all over the world these years. It is meaningful to do some analysis about
it because more and more companies are getting into this business. Since bike sharing is a recent
phenomenon, not that many related analyses have been done upon this topic. However, more and more
bike sharing companies have started to realize the importance of data driven decision making. One of the
major aspects that can be addressed by data analysis is to predict the demand of bikes on any given day.
Knowing the demand would help us in creating a better supply and subsequently reduce the gap between
supply and demand.

Capital bikeshare, established in 2010 and based in Washington DC, is one of the earliest bike sharing
programs and still growing at a good pace. To predict the demand, we have a dataset which includes
hourly rental information of bikes from Capital bikeshare with corresponding weather and seasonal
information for the years 2011 and 2012. By exploring the dataset, we found that the demand for bike is
not constant and varies under different weather conditions. The question here is whether there is a way to
find the balance between demand and supply to achieve better operational efficiency. Hence, we are
conducting this analysis on this dataset is to predict the demand of bikes on any given day and time based
on the information we have. This predicted demand can be used to adjust our supply accordingly and
achieve lower maintenance cost and maximize the profit.

We did a series of analysis to find the best fit model. First, distributions of bike rental counts vs. various
variables (season, month, hour, weather etc.) have been plotted to find how demand changes under
different conditions. Second, OLS regression analysis has been conducted to find the best fit model to
predict the future demand. Based on the information we have, we confirmed that the demand of bike
changes under different conditions (weather, season, hour, temperature, etc.). After several OLS
regression analysis, we found our best fit model to predict the future demand. We also included the
consideration of time series in our best fit model.
