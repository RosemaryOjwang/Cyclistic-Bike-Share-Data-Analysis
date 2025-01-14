# Cyclistic-Bike-Share-Data-Analysis



## Introduction
Welcome to the Cyclistic Bike-Share Analysis Case Study! In this case study, the task is to explore historical bike trip data to understand how casual riders and annual members use Cyclistic bikes differently. The company aims to increase the number of annual memberships, as they are more profitable than casual rides. The marketing team seeks to identify trends and behaviors that can inform a strategy to convert casual riders—who currently use single-ride or full-day passes—into annual members. This analysis will uncover key insights into rider behavior and provide data-backed recommendations to shape future marketing campaigns, ultimately answering the question: **How do annual members and casual riders use Cyclistic bikes differently?**

## Data Description
The dataset used in this analysis includes historical bike trip records from Cyclistic’s bike-share program, specifically from [Divvy 2019 Q1](Datasets/Divvy_Trips_2019_Q1.csv) and [Divvy 2020 Q1](Datasets/Divvy_Trips_2020_Q1.csv), which were combined into a single dataset for analysis. The combined dataset contains a total of 791,956 rows, representing bike trips from both time periods. It captures detailed information on bike rentals, allowing us to compare the behavior of annual members and casual riders. Note that while column names differ slightly between the two datasets, they refer to the same concepts. Below are the key columns in the dataset, separated into **raw data** and **calculated columns**:

### Raw Data Columns:
- ride_id (or trip_id): A unique identifier for each bike trip.
- rideable_type (or bike_type): The type of bike used for the trip (e.g., traditional bike, reclining bike, cargo bike, hand tricycle).
- start_time (or started_at): The timestamp for when the trip began.
- end_time (or ended_at): The timestamp for when the trip ended.
- start_station_name (or from_station_name): The name of the station where the trip started.
- end_station_name (or to_station_name): The name of the station where the trip ended.
- member_casual (or user_type): Indicates whether the rider is a casual rider or an annual member.

### Calculated Columns:
- ride_length: The total duration of the trip in seconds.
- day_of_week: The day of the week the trip occurred.

These datasets cover trips from **Q1 2019** and **Q1 2020**, and by analyzing the trip details, we can identify usage patterns that differentiate casual riders and annual members.

## Data Preprocessing

## Exploratory Data Analysis (EDA)

## Conclusion


