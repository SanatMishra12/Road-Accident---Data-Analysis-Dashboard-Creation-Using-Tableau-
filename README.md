Project Objective : Accident and Road Safety Analysis :

1. To analyze the overall trend of road accidents over time.
2. To identify high-risk regions and accident hotspots using geospatial analysis.
3. To study the severity levels of accidents (fatal, serious, slight).
4. To evaluate casualty patterns based on age group, gender, and road user type.
5. To understand the role of vehicle type involvement in accidents.
6. To provide interactive and visual insights for policymakers, researchers, and safety authorities.

Dataset Used : 
<a href="https://github.com/SanatMishra12/Road-Accident---Data-Analysis-Dashboard-Creation-Using-Tableau-/blob/main/accident_data.csv.gz">Dataset</a>

Question(KPIs) : 

1. What is the total number of accidents over time?
2. Which regions/locations report the highest number of accidents?
3. What is the distribution of accidents by severity (fatal, serious, minor)?
4. What are the common causes of accidents (speeding, drunk driving, weather, road conditions, etc.)?
5. What is the relationship between vehicle type and accident frequency?
6. How many accidents involved casualties vs. non-casualties?
7. Do accidents occur more in urban vs. rural areas?
8. Which vehicle types are most involved in accidents?

Process : 

1. Data Collection – Accident dataset with spatial and categorical details.
2. Data Cleaning & Preparation : 
   Handle missing values for location or light conditions.
   Convert latitude & longitude into mappable points.
   Categorize vehicle types and road types.
   Ensure numeric values for casualties & vehicles.
3. Data Modeling in Tableau : 
   Dimensions → District area, road type, light condition, vehicle type, urban/rural.
   Measures → Accident count, no. of casualties, no. of vehicles involved.   
4. Dashboard Creation : 
   Map View → Accident hotspots by lat/long.
   Bar Charts → Accidents by district, road type, vehicle type.
   Pie/Donut Chart → Share of urban vs. rural accidents.
   KPIs Cards → Total accidents, total casualties, % urban vs rural.
   Heatmap/Tree Map → Impact of light conditions.
5. Interactivity : 
   Filters for district, road type, light condition, urban/rural.
   Drill-down into accident severity and vehicle type


Dashboard Interaction : 

<a href="https://github.com/SanatMishra12/Road-Accident---Data-Analysis-Dashboard-Creation-Using-Tableau-/blob/main/Screenshot%202025-08-16%20190750.png">DashboardScreenshot</a>


Dashboard : 

<img width="1580" height="889" alt="Screenshot 2025-08-16 190750" src="https://github.com/user-attachments/assets/bf0be490-f42b-4d79-83a4-6bde8de10f47" />


Project Insight : 
1. Geographic Hotspots – Certain districts/areas show consistently higher accidents (can be targeted for interventions).
2. Urban vs. Rural – Urban areas may have more accidents due to traffic congestion, while rural areas may show higher fatalities due to poor road conditions.
3. Road Type Analysis – Highways or main roads may contribute to the largest share of casualties.
4. Vehicle Type Trend – Two-wheelers may dominate accident counts, while heavy vehicles may contribute to higher fatalities.
5. Light Conditions – A significant portion of accidents may occur in low-light or dark conditions, suggesting a need for better street lighting.
6. Casualties Correlation – More vehicles involved often lead to higher casualties.


Conclusion : 
1. The Road Accident Dashboard provides a clear, interactive view of accident patterns across districts by analyzing location, road type, light conditions, vehicle involvement, and casualties.
2. It helps identify high-risk areas, accident hotspots, and key contributing factors such as poor lighting, road type, or heavy traffic in urban regions.





