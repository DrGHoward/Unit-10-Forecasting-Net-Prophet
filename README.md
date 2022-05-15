# Unit-10-Forecasting-Net-Prophet
# Introduction

In this assignment we visually depicted various metrics that were of interest to the MercadoLibre company, such as their hourly user search traffic and if this data correlates to thier stock prices. We used a Prophet forecast model to predict hourly user search traffic and we Mined for patterns in seasonality by using visulizations. WIth this information we built sales forecast and user-interest predictive models.

# Methodology

After installing our necessary libraries and dependencies we searched for unusual patterns in hourly Google search traffic. We mined this data for seasonal trends and related these findings to stock price patterns. We used FaceBook Prophet to create a time series model.
We Read the search data into a DataFrame, and then sliced the data to just the month of May 2020. We used this information and hvplot to visualize the result in order to find any unusual patterns. We calculated the total search traffic for the month, and then compared that value to the monthly median across all months.

We grouped the hourly search data to plot the average traffic by the day of the week. We converted this data to a heatmap in order to see any concentrations in any hours of the day. We also mined the data for the weeks of the year to see if search traffic increased during the holiday season.

The stock price data was read in and concatenated with the search data and hvplot was used to plot this data to search for common trends. Stock volitility and hourly stock returns were used for a time series correlation to identify any predictable relationships.
Using our prophet forecasting model, we answered questions such as what time of the day has the most searches, which day of hte week is th emost popular, and what is th elowest point for search trafic during the year.
