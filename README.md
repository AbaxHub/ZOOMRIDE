# ZOOMRIDE SQL Project

Tool used: MYSQL(OneCompiler)

Dataset: ZoomRide is a ride-hailing company in 6 African cities.
with three linked tables:

customers (40 rows) -> who rides.

drivers (20 rows) -> who drives.

trips (300 rows)-> one row per booked trip (links a customer to a driver).

## The manager wants answers to 3 questions:

1. …Which city earns the most money?
   
Answer = Lagos city with  ₦ 218,890 Revenue

3. …Which month do people ride the most?
   
Answer = Month of December 2025 with ₦ 66,980 Revenue and Number of trips to be 31 

5. …Which type of vehicle earns the most money?
   
Answer = Economy with ₦ 5,116,230 Revenue.

## Message to the manager

1…Which city should Zoom Ride invest in? Why?

Answer: Lagos city, currently is giving revenue of ₦ 218,890, which investing more in the city, it will give a very good turnover.

2... two data problems found

 Answers:
 
i. Duplicate of data 
having duplicate in our data, we will result to wrong result in our aggregation


ii. Wrongly spelled data.
if we didn’t fix those wrongly spelled data, we will be having inconsistency in our result with those misspelled cities.

In conclusion working with unstructured data will lead to we making wrong decisions.

3…What is one thing you would like to know more about before a big decision?

Answer:
How to handle the missing values of fare column in the trips table. 

