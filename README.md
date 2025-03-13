# Cyclistic-Bike-Share-Data-Analysis
## Project Overview
This Cyclistic Bike-Share Analysis examines historical trip data to identify usage patterns between casual riders and annual members, aiming to provide data-driven insights that support a marketing strategy for increasing profitable long-term subscriptions.

## Dataset
The dataset for this analysis combines historical bike trip records from Cyclistic’s bike-share program: Divvy 2019 Q1 and Divvy 2020 Q1, totaling 791,956 trips. It details bike rentals, enabling a comparison between annual members and casual riders. Though column names varied slightly, they represented the same concepts. Below are the key columns, categorized as raw data and calculated columns:

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
1. Clone this repository to your local machine:  
   ```
   git clone https://github.com/RosemaryOjwang/Cyclistic-Bike-Share-Data-Analysis.git
   ```
2. Access **RStudio cloud** (also called Posit Cloud) for sign up & Login [here](https://login.posit.cloud/register?product=cloud&redirect=%2Foauth%2Fauthorize%3Fredirect_uri%3Dhttps%253A%252F%252Fposit.cloud%252Flogin%26client_id%3Dposit-cloud%26response_type%3Dcode%26show_auth%3D0)  
3. Click **New Project**, then **New RStudio Project** to create a new project. You can give your project a name.
4. On the bottom right side of the **Posit Cloud** page, click on **Files** > **Upload** > **Choose File** then navigate to the directory holding the cloned repository: https://github.com/RosemaryOjwang/Cyclistic-Bike-Share-Data-Analysis.git. Select **Cyclistic-Bike-Share-Data-Analysis-RScript.R** to upload it into posit cloud.
5. Open the R script (Cyclistic-Bike-Share-Data-Analysis-RScript.R) under **Files** in Posit Cloud.
6. Execute the script by clicking on the **Run** button on the top right of the Posit cloud page.
   **NB:**You can run the code in small batches to avoid errors as we are dealing with a large dataset.
### Expected Output
- Summary statistics printed in the console
- Data visualizations saved in your current working directory.
- Export a summary file for further exploration.
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

