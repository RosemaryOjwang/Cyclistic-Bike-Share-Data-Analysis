# Cyclistic-Bike-Share-Data-Analysis
## Project Overview
This Cyclistic Bike-Share Analysis explores historical bike trip data to understand how casual riders and annual members use the service differently. The goal is to identify trends and behaviors that can help the company increase annual memberships, which are more profitable than one-time rides. By analyzing ride patterns, trip durations, and usage trends, this study provides data-driven insights to support a marketing strategy aimed at converting casual riders into long-term subscribers.

## Dataset
The dataset used in this analysis includes historical bike trip records from Cyclistic’s bike-share program, specifically from [Divvy 2019 Q1](Datasets/Divvy_Trips_2019_Q1.csv) and [Divvy 2020 Q1](Datasets/Divvy_Trips_2020_Q1.csv), which were combined into a single dataset for analysis. The combined dataset contained a total of 791,956 rows, representing bike trips from both time periods. It captures detailed information on bike rentals, allowing the comparison in the behavior of annual members and casual riders. Note that while column names differed slightly between the two datasets, they refered to the same concepts. Below were the key columns in the dataset, separated into **raw data** and **calculated columns**:

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

## How to Run the Code
### Prerequisites
Ensure you have the following installed:  
- **R** (Download from [CRAN](https://cran.r-project.org/))  
- **RStudio** (Optional but recommended)  
- Required R packages (see below)

### Installation
1. Clone this repository to your local machine:  
   ```
   git clone https://[github.com/RosemaryOjwang/Cyclistic-Bike-Share-Data-Analysis](https://github.com/RosemaryOjwang/Cyclistic-Bike-Share-Data-Analysis.git)
   ```
   Navigate to the top level of the directory containing the cloned repository
2. Open R or RStudio and install the required packages:
  ```r  
  install.packages(c("tidyverse", "ggplot2", "dplyr"))  # Add any other dependencies
  ```
### Running the Script
Open the R script (Cyclistic-Bike-Share-Data-Analysis-RScript.R) in RStudio or run it from the terminal.
Execute the script using:
```r
source("Cyclistic-Bike-Share-Data-Analysis-RScript.R")
```
#### The script will:
- Load and clean the dataset
- Perform exploratory data analysis
- Generate visualizations and summaries

### Expected Output
- Summary statistics printed in the console
- Data visualizations saved in your current working directory.

N/B: For any issues, check for missing dependencies or errors in the dataset format.

## Analysis Steps
1. Collect data.
2. Wrangle data and combine into a single file.
3. Clean up and add data to prepare for analysis.
4. Conduct descriptive analysis.
5. Export summary file for further analysis.

## Results & Visualizations
The analysis identified key differences between casual riders and annual members, helping shape data-driven marketing strategies.  

**View the full presentation here:** [Cyclistic Analysis Presentation](https://docs.google.com/presentation/d/1w4xdPxZvyavPg2ct1LWB8wuOGEEZJnSyNn3NWAEboTc/edit?usp=sharing)  

## Technologies Used
- Programming Language: R
- Libraries/ Packages: tidyverse, dplyr, scales and conflicted.

## License
[MIT](https://opensource.org/license/mit)

## Contact/ Author
- [My GitHub Profile](https://github.com/settings/profile)
- [My LinkedIn Profile](www.linkedin.com/in/rosemary-ojwang-989b76259)

