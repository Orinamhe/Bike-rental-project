# Bike-rental-project
Utilised SQL, Microsoft Excel and Power BI to explore the bike rental information in parts of Budapest


![image](https://github.com/Orinamhe/Bike-rental-project/assets/153821560/ab5f3478-2bf1-41a3-afe0-ec564fe46120)


REPORT SUMMARY
UNDERSTANDING TASK OBJECTIVE
Important questions which would provide information to answer the tasks included:
-	What is the trend (monthly, daily, hourly and half-hourly) in bike rental?
-	What stations/rental points have bikes been rented from the most? 
-	What is the destination station of most rented bikes?
-	Rank route (start station – end location) based on bike usage.
-	How does weather affect lending? 

ETL
PostgreSQL was used to extract and transform the data to provide quick exploratory insights needed to answer the questions. Refer to supplementary document (supplementary_data.pdf). 

DATA ANALYSIS AND VISUALIZATION
To prepare appropriate visuals for the analyzed data, ETL was done by Power BI. Power query editor was used to further transform the data in the tables to appropriate format. Various DAX measures were used to generate measures. See the Power BI dashboard (Bike_rental_report_dashboard) for data visualization.

INSIGHTS/RECOMMENDATIONS
Refer to Bike_rental_report_dashboard for analysed visual representation.
Bike rental activity exhibited a rising trend over the course of the year, with the lowest bike renting activity in January, and May registering the highest bike rental. Analyzing the hourly timeframe in each day and month, showed that most bike rentals occurred between 15:00 - 18:00, with 17:00 being the peak time.

It is common for people to be less inclined to rent bikes in unfavourable weather conditions and as such analyzing the effects of weather factors on bike rental activity yielded certain insights.  Temperature and humidity emerged as key weather factors influencing bike rental activity across the months. The average temperature demonstrated a positive correlation with bike rentals, evident in the coldest month (January) having the lowest rental activity, while May, characterized by the highest average temperature, recorded the peak in bike rentals. This positive correlation makes sese as people are more likely to rent bikes during warmer months.
 Conversely, humidity exhibited a negative correlation with bike rentals, indicating fewer rentals on more humid days. The observation that humidity, snow, and fog reduced as the year progressed aligns with typical seasonal patterns. Warmer months (spring) often have lower humidity and less likely to experience snow and fog, contributing to increased bike rentals.

The hourly peak period for bike renting appeared to be affected by temperature and humidity, as the period between 15:00 - 18:00 had the lowest humidity and highest temperature in each day In each month, days with significant rainfall had low bike rental activity.

To recommend locations for advertisement placement, it was important to identify the most frequently used stations in the dataset. Frequency of use was measured by determining the most used docking stations as starting points for renting bicycles and destination stations after bike rental. The busiest stations based on analysis were:
1.	Margitsziget
Number of starts: 3,336
Number of ends: 3,333
2.	Kálvin tér
Number of starts: 2,904
Number of ends: 3,085
3.	Erzébet tér 
Number of starts: 2,882.
Number of ends: 2,751

Based on this result, these stations are recommended as good points for the advertisement to set up ads.

Additionally, the most used route (start location to end location after bike rental) and the number of these bike trips were also counted as shown below.
Margitsziget – Margitsziget      - 1022
Jászai Mari tér -  Margitsziget   - 513	  
Margitsziget  - Jászai Mari tér   - 338


