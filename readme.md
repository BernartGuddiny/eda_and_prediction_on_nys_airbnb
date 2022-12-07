# Data Exploration on NYS Airbnb and Price Prediction
![python 3.9.1](https://img.shields.io/pypi/pyversions/pandas?color=green&label=python)
![pandas 1.5.2](https://img.shields.io/badge/pandas-1.5.2-blue)
![seaborn 0.12.1](https://img.shields.io/badge/seaborn-0.12.1-brightgreen)
![scikit-learn 1.1.3](https://img.shields.io/badge/scikit--learn-1.1.3-orange)

### **Introduction**
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.

### **The designation of the columns in the dataset:**
- id - listing ID;
- name - name of the listing;
- host_id - host ID;
- host_name - name of the host;
- neighbourhood_group - location;
- neighbourhood - area;
- latitude - latitude coordinates;
- longitude - longitude coordinates;
- room_type - listing space type;
- price - price in dollars;
- minimum_nights - amount of nights minimum;
- number_of_reviews - number of reviews;
- last_review - latest review;
- reviews_per_month - number of reviews per month;
- calculated_host_listings_count - amount of listing per host;
- availability_365 - number of days when listing is available for booking.

### **The main task**
In this Jupyter Notebook I have tried to Exploratory Data Analysis (EDA) and find a correlation between price and any categorical data. And I also created models for predicting that how rental price is varying in New York City based on different features.