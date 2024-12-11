# Nyc-Collisions
![](https://github.com/Chisom-Blessing/Nyc-Collisions/blob/main/nyc_image.jpg)
# Introduction
This project aims to provide an in-depth analysis of traffic collision data in **New York City**, using advanced data visualization techniques in Power BI. By exploring accident patterns across various dimensions such as month, day of the week, time of day, and location, this analysis seeks to uncover key trends that can inform safety measures and help reduce traffic-related incidents.
The dataset used in this analysis includes detailed information on the frequency of accidents, contributing factors, and accident severity (injuries and fatalities). The goal is to identify patterns that can be leveraged to make data-driven decisions, improve road safety, and guide targeted interventions by policymakers and city planners.
This document will outline the methodology used to process and analyze the data, present the key findings, and provide actionable recommendations based on the insights derived from the analysis. 
By providing a clear understanding of when, where, and why accidents occur most frequently, this analysis offers valuable insights for both public safety efforts and traffic management strategies in New York City.

# Problem statement

1.	Compare the % of total accidents by month. Do you notice any seasonal patterns?
2.	 Break down accident frequency by day of week and hour of day. Based on this data, when do accidents occur most frequently? 
3.	 On which particular street were the most accidents reported? What does that represent as a % of all reported accidents? 
4.	 What was the most common contributing factor for the accidents reported in this sample (based on Vehicle 1)? What about fatal accidents specifically?

# Data model

![](https://github.com/Chisom-Blessing/Nyc-Collisions/blob/main/model_view.png)

# Analysis

Here are the answers to the problem statement are the analysis done:

1. Comparison of Total Accidents by Month and Seasonal Patterns
Based on the analysis of accident data across different months, the following trends were observed. Top 5 months with the highest accident counts:
- March: 25,099 accidents
- January: 23,024 accidents
- February: 21,207 accidents
- June: 20,079 accidents
- May: 19,749 accidents
In terms of seasonal breakdown:
- Spring (March, April, May) exhibited the highest accident frequency, accounting for 26.86% of all reported accidents.
- Winter (December, January, February) followed with 25.66% of the total accidents.
- Summer (June, July, August) contributed 24.22%, while Fall (September, October, November) represented 23.26% of the total incidents. This data suggests that spring, particularly March, sees a peak in accidents, which could be attributed to factors like weather transitions, increased travel activity, or other seasonal variables.

![](month.png)

![](season.png)

2. Accident Frequency by Day of the Week and Hour of the Day
Further analysis reveals the following insights regarding accident frequencies by day of the week and hour. The most frequent accidents occurred on the following days:
- Friday: 2,447 accidents
- Wednesday: 2,379 accidents
- Thursday: 2,314 accidents. In terms of timing, the majority of accidents occurred at 16:00 hrs (4:00 PM) across these days.
This pattern suggests that accidents are most frequent during weekday afternoons, particularly as traffic congestion peaks around rush hour. This could be linked to factors such as increased driver fatigue, distractions, and high vehicle volume during this time.

![](hour.png) 

3. Accident Frequency by Street
When analyzing accidents based on location, the following streets recorded the highest number of incidents:
- Belt Parkway: 3,728 accidents (28.51% of total accidents)
- Broadway: 2,794 accidents (21.37%)
- Atlantic Avenue: 2,230 accidents (17.05%)
- Long Island: 2,165 accidents (16.56%)
- Brooklyn Queens: 2,159 accidents (16.51%). Belt Parkway was identified as the street with the highest number of accidents, contributing a significant 28.51% of the total incidents. This high frequency may be due to factors such as heavy traffic, complex road conditions, or congestion. Further investigation into road safety measures on this street could be beneficial.

4. Most Common Contributing Factors for Accidents and Fatalities
The analysis of contributing factors for accidents, revealed the following top causes:
- Unspecified causes: 59,549 accidents
- Driver inattention/distraction: 58,308 accidents
- Failure to yield right of way: 16,555 accidents
- Following too closely: 15,519 accidents
- Improper passing or lane usage: 10,733 accidents. The most common contributing factor for accidents was unspecified causes, followed closely by driver inattention/distraction, which highlights the significant role human error plays in accidents. These findings emphasize the importance of addressing driver behavior, such as distractions and inattention, in efforts to reduce accidents.

# Key findings and Recommendation
1. Targeted Safety Improvements in High-Accident Areas
- Belt Parkway and Other High-Incident Streets: Given that Belt Parkway accounted for 28.51% of total accidents, immediate attention should be given to improving safety measures along this route. Measures such as enhanced signage, better lighting, clearer lane markings, and increased enforcement of traffic laws could be considered. Additionally, infrastructure improvements such as traffic flow management, ramp redesigns, or dedicated lanes for different vehicle types could reduce congestion and accidents.


**Recommendation**: Conduct a detailed traffic flow and accident investigation on Belt Parkway, Broadway, and Atlantic Avenue to identify specific causes (e.g., poor signage, construction zones, or high traffic volumes) and implement targeted safety improvements.

 2. Addressing High-Risk Times and Days
- Peak Accident Times: Accidents tend to occur more frequently on Fridays, Wednesdays, and Thursdays around 16:00 hrs (4:00 PM). This correlates with increased traffic volume due to rush hour. Implementing measures such as enhanced traffic management, ramp metering, and public awareness campaigns around these peak times could help mitigate congestion and reduce accidents.


**Recommendation**:
- Launch public awareness campaigns reminding drivers to stay alert during peak hours, particularly in the afternoon.
- Increase law enforcement visibility and traffic monitoring during these times to reduce speeding and distracted driving.
- Consider adjusting traffic light cycles to better manage congestion during rush hour, particularly at intersections where accidents are more frequent.


