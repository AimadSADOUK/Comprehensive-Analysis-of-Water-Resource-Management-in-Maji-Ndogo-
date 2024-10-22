# Comprehensive Analysis of Water Resource Management in Maji Ndogo (Restoring the lifeblood of Maji Ndogo)
© ExploreAI Academy
Project realised by: Aimad SADOUK

### Project Description:
At the heart of this project lies the pressing water crisis in the fictitious country of Maji Ndogo. During my training with Explore AI Academy, I was tasked with exploring this critical issue, which provided a unique opportunity to dive deep into the complexities of SQL. Throughout this journey, I tackled intricate problems that required critical thinking and innovative solutions.
The project was designed to progressively challenge me, offering less guidance as I advanced, which pushed me to enhance my problem-solving skills. Over the course of five weeks in the SQL module, I not only gained a profound understanding of SQL but also developed a strategic blueprint for approaching future challenges. This experience has equipped me with the tools and insights necessary to address complex issues in water resource management, ultimately contributing to a better understanding of the obstacles faced by communities in Maji Ndogo.

![image alt text](https://github.com/AimadSADOUK/Comprehensive-Analysis-of-Water-Resource-Management-in-Maji-Ndogo-/blob/main/EXPLORE%20AI%20ACADEMY.PNG?raw=true)
![image alt text(https://github.com/AimadSADOUK/Comprehensive-Analysis-of-Water-Resource-Management-in-Maji-Ndogo-/blob/main/Maji%20Ndogo.PNG?raw=true)
## employee_Table:
The Maji Ndogo dataset reveals 56 unique employees. Hawassa leads with 15 employees, followed by Akatsi (13) and Kilimani (12). The town of Rural has the highest count at 29 employees, indicating it as a central hub. The Field Surveyor position is the most common, with 29 employees, reflecting a strong emphasis on fieldwork. Average employee counts show Kilimani (Rural) at 9.00, and both Hawassa (Rural) and Sokoto (Rural) at 7.00, highlighting staffing needs in rural areas.
Insights:
Hawassa and Rural are key operational areas.
A focus on Field Surveyors suggests priority on data collection.
Rural towns may benefit from increased staffing to improve service delivery.

## location_table:
Distribution of Locations: What is the distribution of different location types (urban/rural) across various provinces?
Top Towns by Locations: Which towns have the highest number of recorded locations in each province?
Province Comparison: How does the number of locations compare across different provinces?
Rural Areas Dominate:
Akatsi has 6,290 rural locations, followed by Kilimani with 5,440, and Sokoto with 5,010.
Rural locations make up a significant portion of the total, e.g., Akatsi's rural locations represent 70% of its total locations.
Top Towns:
Akatsi's rural area leads with 6,290 locations.
Urban areas like Lusaka (1,070 locations) and Mrembo (990 locations) follow, but rural areas account for the majority—69% of the top 10 recorded locations are rural.
Provincial Comparison:
Kilimani leads with 9,510 total locations (22.6% of the total), followed by Akatsi with 8,940 (21.3%), and Sokoto with 8,220 (19.5%).
Hawassa has the fewest locations, representing 14.3% of the total, potentially indicating underserved areas.

## visits_table:
Visits Volume: What are the busiest times of day for visits across different locations?
Waiting Time Analysis: What is the average time spent in queue per visit in each town or province?
Employee Efficiency: Which employees are associated with the most visits, and what is the average wait time for each?

Busiest Times of Day: Visits peak between 1 PM and 2 PM, with over 6,600 visits, indicating the need for more resources during early afternoon.
Queue Time by Town/Province: Zuri (Kilimani) has the longest average wait time at 118 minutes, while Yaounde (Hawassa) experiences the shortest at 11 minutes.
Employee Performance: Bello Azibo handled the most visits (3,708), but Xola Uzuri had the lowest average wait time (49 minutes) while managing a significant workload.
water_source table:
Water Source Type Distribution: What is the distribution of water source types across different regions or towns?
Water Source vs. Population Served: Which water sources serve the largest number of people in each region or town?
Water Source Popularity: Which water source types are most frequently visited?

Water Source Type Distribution: The distribution of water source types shows that shared taps account for 7,239 visits in Kilimani and 6,268 in Akatsi, indicating a significant reliance on shared water sources.
Water Sources Serving Largest Populations: In Akatsi, the shared tap serves the largest population with 13,073,894 people, emphasizing the critical role of shared taps in water accessibility across regions.
Most Frequently Visited Water Sources: The most frequently visited water source type is shared taps with 26,263 visits, followed by wells with 17,383 visits and tap in homes with 7,265 visits, suggesting a preference for easily accessible water sources among the population.

## well_pollution table:
   10. Pollution Trends: Which pollutants (in ppm) are most prevalent in different regions over time ?
   11. Pollution Impact: What is the relationship between the level of pollution and the water quality rating in different locations?
   12. Pollution Type Analysis: Which towns or provinces report the most instances of biological pollution compared to chemical pollution?
E. coli bacteria appears as the most prevalent pollutant in provinces like Kilimani, Hawassa, and Sokoto, especially in 2022 and 2021, with Kilimani leading in the number of occurrences (168 and 164 instances in 2022 and 2021, respectively).
Pollution Impact:
In provinces such as Akatsi and Sokoto, regions with high pollution levels (with 9.99 ppm), the water quality ratings remain consistently low at 2.00, suggesting a direct negative correlation between higher pollution levels and poor water quality ratings.
Pollution Type Analysis:
Provinces like Akatsi and Kilimani report the highest number of chemical pollution instances, particularly in rural areas. For example, Akatsi Rural alone had 1,685 instances of chemical pollution, while biological pollution is significantly less frequent across these regions.

## Visits + Water Source Table (Joins):
13. Visit Count per Water Source: Which water sources have the highest visit counts in each town or province?
14. Queue Time by Water Source: What is the average queue time for each type of water source across different locations?
15. Water Source Utilization: How do the number of visits and the population served correlate for each water source type?

Highest visit counts: Shared taps in Akatsi (5,774), Kilimani (4,900), and Sokoto (4,138) have the most visits.
Queue time: Kilimani has the longest average wait for shared taps (139.71 minutes), followed by Sokoto (136.60 minutes).
Water source utilization: All water sources, including taps and wells, have very low utilization ratios compared to the population served.

## Other Questions:
16. How can we summarize the total number of visits managed by each employee, their average queue time, and rank them by visit count, displaying only the top 10 employees?
17. What are the yearly pollution trends categorized by pollutant levels (Low, Moderate, High) across different provinces, and how many occurrences fall into each category?
18. How can we analyze monthly visit trends, including the total number of visits and the average queue time for each town, and rank them to display the top 5 towns by visit count each month?
19. What is the total number of people served by each type of water source, the total number of visits associated with each source, and how can we rank the top 3 water sources based on the number of people served?
20. How can we analyze the relationship between well pollution levels, water quality scores, and regions, displaying the towns with the lowest average water quality scores while accounting for pollution levels?

Top Employees: Bello Azibo stands out as the highest-performing employee with 3,708 visits, followed closely by Pili Zola and Rudo Imani.
Average Queue Time: Employees like Farai Nia and Enitan Zuri maintain relatively low average queue times, suggesting efficiency in managing visits.

Yearly Trends: The analysis reveals a consistent occurrence of "Low" and "Moderate" pollution levels across provinces like Akatsi and Amanzi, indicating potential environmental concerns.
Monitoring Needed: Continuous monitoring of pollutant levels is crucial, especially in years with increasing occurrences.

Top Towns: Akatsi frequently appears among the top towns for visits, indicating its significance in the region.
Monthly Variations: Fluctuations in visits highlight seasonal trends, which may be linked to factors such as public health campaigns or environmental changes.

Popular Sources: Shared taps serve the highest number of people, suggesting their importance in the community.
Service Ranking: Well and home taps follow, highlighting the need for maintaining these sources for sustainability.

Quality and Pollution Correlation: Towns like Hawassa exhibit low average water quality scores alongside varying pollution levels, indicating potential risks to public health
Focus Areas: Regions with the lowest scores should be prioritized for interventions to improve water quality and reduce pollution.













