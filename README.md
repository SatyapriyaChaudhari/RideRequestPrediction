# Ride Request Prediction
***

### Problem Statement: 

We have a year of data for each time a customer has requested for a ride. Can we try and predict ride requests for the future?
***

### About the Data:

The data is stored in this format - timestamp, customer_id, pickup request latitude, pickup request longitude, drop request latitude, drop request longitude. A snapshot of the data is below.

![Rapido1.png](attachment:Rapido1.png)

There were 8122696 ride requests recorded.
***

### Data Analysis:
***
* These 8122696 observations were recoreded over a span of 363 days.
***
* From the data, it was clearly visible that both the trend and seasonality was present in the data.
![Rapido2.png](attachment:Rapido2.png)
***
* The time series is not stationary.
***
* Clear spike in the data at every seven day interval
![Rapido3.png](attachment:Rapido3.png)
![Rapido4.png](attachment:Rapido4.png)
***

### Prediction for Next 90 days:
***

* Based on the forecasted data, the marketing strategy can be planned for the upcoming months.

![Rapido5.png](attachment:Rapido5.png)

***

* Increasing pattern in the ride request is seen in the forecasted data.
* Forecasted ride request during the weekday is much more than the weekends.

![Rapido6.png](attachment:Rapido6.png)

***

An abrupt change in the trajectory of the time series is usually seen once in the middle and once towards the end of almost every month.

***

### Next Steps:
***

This analysis was done on the entire dataset, however this can be further broken down based on locations and different points in times during the days.


```python

```
