# NYC-TAXI-FARE-PREDICTION
<center><img src="https://i0.wp.com/www.businesstraveller.nl/wp-content/uploads/2019/08/mmnmnn.jpg?fit=2560%2C1600&ssl=1" width=700></center>
# Objective
 
This dataset is a record of taxi trips in New York City.
 These are the features of this dataset: Amount, date_time_of_pickup, longitude_of_pickup, latitude_of_pickup, longitude_of_dropoff        ,latitude_of_dropoff,no_of_passenger,hour,is_weekend,distance,minute,time_slot,is_holiday.

Training observations are labeled with the fare amount paid.

Our objective is to create a model that will accurately estimate the fare amount of trips in the test dataset. Accuracy is measured by root mean square error.

We will also be performing exploratory data analysis in an attempt to better understand the dataset

# Results

### Modeling

* A Rendom Forest Regressor This model has 15 features, making the most use of the Distance,Hour and Time_slot.
* The leaderboard RMSE obtained by this model is 2.44.


