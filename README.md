# Cyclistic-bike-share-analysis
🚲 **Cyclistic Q1 2020 Data Analysis**

This project is the capstone for the Google Data Analytics Professional Certificate, where I analyzed historical trip data from Cyclistic's Q1 2020 dataset to explore behavioral differences between casual riders and annual members.

## 📊 Business Task
To support Cyclistic’s marketing strategy, I analyzed how annual members and casual riders use the service differently. The goal was to uncover trends in usage (ride durations, times, days, and frequency) and recommend ways to convert casual riders into annual members.

### 🧩 Dataset
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Source: Divvy Bike Share System Open Data Portal
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;File: Divvy_Trips_2020_Q1.csv
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Size: ~427,000 rows of ride data

### Key Fields: 
```
  ride_id, rideable_type, started_at, ended_at,
  
  start_station_name, end_station_name,
  
  start_lat, start_lng, end_lat, end_lng
  
  member_casual (User type: "member" or "casual")
  ```

### 🔧 Data Cleaning & Tools Used
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Google BigQuery*** for data cleaning, outlier detection, and calculation.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Google Sheets*** for weekday extraction and prep for visualization.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Tableau*** for dashboards and visual analysis.

### 🧹 Cleaning Steps:
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Removed invalid/negative timestamps and extreme outliers.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Filtered by percentiles to reduce data noise.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sampled 4,000 rides (99% confidence level, ~2% margin of error).

### 📈 Key Insights
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Annual members: Ride mostly on weekdays, shorter durations → likely commute use.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Casual riders: Ride longer, mainly on weekends → likely leisure use.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Casuals ride most around midday and afternoon hours.

### 📌 Recommendations
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Launch a Weekend Membership Plan for casual riders.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Promote memberships at high-traffic casual-dominant stations.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Adjust pricing for midday rides to attract casuals.
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. Introduce loyalty rewards based on ride duration.

### 📍 Visualizations
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Check out the full interactive dashboard on Tableau:
  🔗 [Cyclistic Q1 2020 Annual VS Casual Dashboard on Tableau](https://public.tableau.com/app/profile/ashraf.un.noor/viz/CyclisticQ12020AnnualVSCasual/Dashboard2) 

### 🧠 Skills Demonstrated
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - ***Data wrangling with SQL (BigQuery)***
  
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - ***Sampling and statistical analysis***
  
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - ***Data cleaning and transformation***
  
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - ***Data storytelling with Tableau***
  
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - ***Problem-solving using real-world business context***
