# Taxi-Demand-Prediction-in-New-York-City

## Project Overview
<p> There are roughly 200 million taxi rides in New York City each year. Exploiting an understanding of taxi supply and demand could increase the efficiency of the city’s taxi system. In the New York city, people use taxi in a frequency much higher than any other cities of US. Instead of booking a taxi by phone one day ahead of time, New York taxi drivers pick up passengers on street. The ability to predict taxi ridership could present valuable insights to city planners and taxi dispatchers in answering questions such as how to position cabs where they are most needed, how many taxis to dispatch, and how ridership varies over time. Our project focuses on predicting the number of taxi pickups given a time window and a region within New York City. </p>

## Problem Statement
This is a supervised learning problem where we need to predict the number of pickups given a 10 min time interval and a region in the New york city. Some location require more taxis at a particular time than other locations owing to the presence schools, hospitals, offices etc. The prediction result can be transferred to the taxi drivers via Smartphone app, and they can subsequently move to the locations where predicted pickups are high. The goal is to predict the no of pickups with minimum Mean Absolute percentage error.

## Install
This project requires Python 3.5 and the following Python libraries installed:

  * NumPy
  * Pandas
  * dask
  * folium
  * gpxpy
  * matplotlib
  * scikit-learn
  * tensorflow
  * seaborn
  * wordcloud
  * Xgboost
You will also need to have software installed to run and execute an iPython Notebook

We recommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Data Source 
http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml. 

## Code
The code is provided in the TaxiDemandPrediction.ipynb notebook file. 

## Data
To solve the problem we would be using data collected in Jan - Mar 2015 to predict the pickups in Jan - Mar 2016. 

<table align = 'left'>
<tr>
<th> file name </th>
<th> file name size</th>
<th> number of records </th>
<th> number of features </th>
</tr>
<tr>
<td> yellow_tripdata_2016-01 </td>
<td> 1. 59G </td>
<td> 10906858 </td>
<td> 19 </td>
</tr>

<tr>
<td> yellow_tripdata_2016-02 </td>
<td> 1. 66G </td>
<td> 11382049 </td>
<td> 19 </td>
</tr>
<tr>
<td> yellow_tripdata_2016-03 </td>
<td> 1. 78G </td>
<td> 12210952 </td>
<td> 19 </td>
</tr>

</tr>
<tr>
<td> yellow_tripdata_2015-01 </td>
<td> 1.84Gb </td>
<td> 12748986 </td>
<td> 19 </td>
</tr>
<tr>
<td> yellow_tripdata_2015-02 </td>
<td> 1.81Gb </td>
<td> 12450521 </td>
<td> 19 </td>
</tr>
<tr>
<td> yellow_tripdata_2015-03 </td>
<td> 1.94Gb </td>
<td> 13351609 </td>
<td> 19 </td>
</tr>
</table>

**Features**
  * VendorID
  * tpep_pickup_datetime 
  * tpep_dropoff_datetime
  * passenger_count
  * trip_distance
  * pickup_longitude
  * pickup_latitude
  * RateCodeID
  * store_and_fwd_flag
  * dropoff_longitude
  * dropoff_latitude
  * payment_type
  * fare_amount
  * extra
  * mta_tax
  * tip_amount
  * tolls_amount
  * improvement_surcharge
  * total_amount
