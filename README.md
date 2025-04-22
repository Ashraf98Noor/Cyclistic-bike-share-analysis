# Cyclistic-bike-share-analysis
🚲 Cyclistic Q1 2020 Data Analysis
This project is the capstone for the Google Data Analytics Professional Certificate, where I analyzed historical trip data from Cyclistic's Q1 2020 dataset to explore behavioral differences between casual riders and annual members.

📊 Business Task
To support Cyclistic’s marketing strategy, I analyzed how annual members and casual riders use the service differently. The goal was to uncover trends in usage (ride durations, times, days, and frequency) and recommend ways to convert casual riders into annual members.

🧩 Dataset
Source: Divvy Bike Share System Open Data Portal

File: Divvy_Trips_2020_Q1.csv

Size: ~427,000 rows of ride data

Key Fields:
ride_id, rideable_type, started_at, ended_at,

start_station_name, end_station_name,

start_lat, start_lng, end_lat, end_lng

member_casual (User type: "member" or "casual")

🔧 Data Cleaning & Tools Used
Google BigQuery for data cleaning, outlier detection, and calculation.

Google Sheets for weekday extraction and prep for visualization.

Tableau for dashboards and visual analysis.

Cleaning Steps:
Removed invalid/negative timestamps and extreme outliers.

Filtered by percentiles to reduce data noise.

Sampled 4,000 rides (99% confidence level, ~2% margin of error).

📈 Key Insights
Annual members: Ride mostly on weekdays, shorter durations → likely commute use.

Casual riders: Ride longer, mainly on weekends → likely leisure use.

Casuals ride most around midday and afternoon hours.

📌 Recommendations
Launch a Weekend Membership Plan for casual riders.

Promote memberships at high-traffic casual-dominant stations.

Adjust pricing for midday rides to attract casuals.

Introduce loyalty rewards based on ride duration.

📍 Visualizations
Check out the full interactive dashboard on Tableau:
🔗 [Cyclistic Q1 2020 Annual VS Casual Dashboard on Tableau](https://public.tableau.com/views/CyclisticQ12020AnnualVSCasual/Map?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) 

🧠 Skills Demonstrated
Data wrangling with SQL (BigQuery)

Sampling and statistical analysis

Data cleaning and transformation

Data storytelling with Tableau

Problem-solving using real-world business context
