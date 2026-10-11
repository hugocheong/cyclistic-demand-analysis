# Cyclistic Customer Demand Analysis

## Overview
This project is part of the Google Business Intelligence Professional Certificate and focuses on analyzing customer demand patterns for **Cyclistic**, a fictional bike-sharing company. The goal is to provide actionable insights to optimize station placements and enhance marketing strategies. The analysis uses NYC Citi Bike trip data with Census Bureau boundaries for neighborhood and zip code lookups.

---

## Tools and Techniques
- **Tableau**: Developed 3 dashboards to visualize customer demand patterns, high-demand stations, and seasonal trends.
- **Google BigQuery**: Managed large datasets with SQL queries for data cleaning, transformation, and analysis.
- **SQL**: Wrote queries to join trip, weather and location data and aggregate it for the dashboards.
- **ETL Process**: Extracted, transformed, and loaded large datasets to prepare for analysis.

---

## Project Objectives
- **Station Optimization**: Identify high-demand stations to improve resource allocation and plan for new station placements.
- **Behavioral Analysis**: Examine customer ride patterns, focusing on peak usage times and durations.
- **Marketing Strategy**: Inform targeted campaigns by understanding seasonal trends and customer segmentation.

---

## Process

### 1. **Data Collection**
   - Extracted datasets containing ride details (start and end times, locations), customer types, and timestamps.

### 2. **Data Cleaning and Transformation**
   - Applied ETL processes in Google BigQuery to clean and preprocess raw data.

### 3. **Data Analysis**
   - Identified high-demand starting and destination areas by trip count and total trip minutes.
   - Mapped monthly trip totals to show seasonal peaks and troughs.
   - Analyzed ride duration patterns across different customer types (casual customers vs. subscribers).

### 4. **Dashboard Development**
   - Created 3 dashboards in Tableau:
     - **Summer Trends**: Map and table of trips by starting and ending neighborhood, split by customer type, with July, August and September maps.
     - **Seasonality**: Monthly trip totals by customer type, and trip counts by starting neighborhood and zip code.
     - **Top Trips**: Total trip minutes by starting station and by destination.

---

## Key Findings
- About 3.5 million trips (3,499,028) from December 2018 to December 2020.
- Subscribers took 84% of trips (2,924,501), and casual customers took 16% (574,527).
- Casual customers ride about twice as long as subscribers: 31 minutes on average, against 15.
- Trips peak in late summer and drop to a low each winter.
- Chelsea and Clinton (10011) is the top starting area, and Lower East Side (10002) the top destination, each at about 5.5 million trip minutes.

---

## Dashboards
The interactive dashboards are publicly accessible on Tableau Public:  
[**Cyclistic Case Study Dashboards**](https://public.tableau.com/views/CyclisticCaseStudy_17188499515650/CyclisticExemplar?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---


## Conclusion
This project turns millions of trip records into three dashboards that show where and when demand concentrates, and how casual customers and subscribers ride differently. Stakeholders can use them to plan new stations and time seasonal campaigns.
