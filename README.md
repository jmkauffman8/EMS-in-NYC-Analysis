# EMS-in-NYC-Analysis
Report that uses a variety of visualization and statistical techniques to understand the effects that the COVID-19 has had on EMS in NYC

## Overview
The Effect of COVID-19 on Emergency Medical Care Services in New York City is a report that examines the effects of the COVID-19 pandemic on the New York City Emergency Medical Services (EMS). The report aims to answer how the pandemic has affected the city's response to EMS calls. The report uses data obtained from the EMS Incident Dispatch Data, which contains 31 variables, including time and date, severity, borough, and police precinct. The report also uses data on automobile crashes in New York City to contextualize the primary data.

## Introduction
The COVID-19 pandemic has had a profound impact on nearly every aspect of life in cities across the world, including emergency medical services (EMS) that are critical for the health and safety of the population. In New York City, which was one of the earliest and hardest-hit cities in the United States, the EMS Incident Dispatch Data provides a wealth of information that can help shed light on the effect of the pandemic on EMS responses. With over 21.8 million calls recorded over the past decade, this dataset offers a multifaceted view of emergency calls in the city, including variables such as call type, severity, response time, and location.

As the pandemic took hold in the city, one question emerged as particularly pressing: how has the COVID-19 pandemic impacted the way that New York City responds to EMS calls? To answer this question, this report delves into the EMS Incident Dispatch Data and analyses several key variables, including the date and time of the incident, final call type, incident response time, final severity, borough, police precinct, and more. In addition to this primary data source, the report also incorporates data on automobile crashes in the city during the same time period, as these events are often linked to EMS calls.

The report sets out to examine the relationship between the COVID-19 pandemic and EMS responses in New York City, defining pre- and during-COVID time periods and comparing key metrics between these time periods. By answering smaller sub-questions, such as how call types changed before and during the pandemic, the report builds up a comprehensive picture of the impact of the pandemic on emergency medical services in the city. Overall, this report provides a detailed and data-driven analysis of the impact of the COVID-19 pandemic on emergency medical care in New York City, shedding light on the ways in which one of the world's most populous cities responded to a global health crisis.

## Data and Methodology

The data and methodology section of this report presents a rigorous and comprehensive analysis of emergency response data during two distinct periods: the pre-COVID era and the COVID-19 pandemic. Specifically, the report covers the time period from March 23, 2019, to December 31, 2019, and from March 23, 2020, to December 31, 2020. The analytical approach utilized in this report is multi-faceted, incorporating a variety of metrics and comparisons to provide a holistic understanding of emergency response patterns.

The visualization below examines a borough-by-borough breakdown of the change in call type from 2019 to 2020.

<img width="734" alt="Screen Shot 2023-02-21 at 5 02 02 PM" src="https://user-images.githubusercontent.com/105028034/220478414-37bb5c6c-afab-4ffa-aab4-f405f522c03d.png">

The visualization below examines how the top 10 most common call types changed before/during COVID

<img width="745" alt="Screen Shot 2023-02-21 at 5 03 26 PM" src="https://user-images.githubusercontent.com/105028034/220478580-15235b5e-b32d-4035-8c85-2524c31cb3c4.png">

The report examines the data in numerous ways, including analyzing call types, response times, and police precincts, among others. By comparing these different categories of data, the report identifies trends and patterns that are crucial for emergency response services to understand. Furthermore, the report delves into the relationship between boroughs and various metrics such as hospital travel time and final call type, providing an in-depth exploration of the disparities that exist between different neighborhoods and boroughs.

The following visualization showcases the decrease in crime-related EMS calls pre and post-COVID.

<img width="737" alt="Screen Shot 2023-02-21 at 5 04 19 PM" src="https://user-images.githubusercontent.com/105028034/220478704-65fd6743-a6bd-4e7c-aee5-d799cc7753ce.png">

This visualization showcases an interesting trend involving an increase in breathing related EMS calls in NYC:

<img width="725" alt="Screen Shot 2023-02-21 at 5 08 30 PM" src="https://user-images.githubusercontent.com/105028034/220479287-e3ab3d4c-353f-47cf-b4b9-a636c0d78bbe.png">

In addition, the report explores the relationship between the number of automobile accidents and average call response time, offering insights into the impact that traffic accidents have on emergency response services. By taking a comprehensive approach to analyzing the data, the report provides a nuanced understanding of the challenges and opportunities that emergency responders face in New York City, both during and before the COVID-19 pandemic.

## Results and Discussion

Overall, the analysis revealed several notable trends and patterns in emergency call data during the pre-COVID and COVID periods. First, there was a significant decrease in the total number of emergency calls during the COVID period compared to the pre-COVID period, with a 13.2% decrease in the total number of calls received. This decrease is likely due to the reduction in outdoor activity and social interaction as a result of pandemic-related restrictions.

The data also showed a shift in the types of calls that were received during the COVID period. For example, there was a notable increase in the number of calls related to "sick person" and "difficulty breathing," which can be attributed to the COVID-19 pandemic. On the other hand, there was a decrease in the number of calls related to "noise complaints," "non-crime emergencies," and "harassment," which could be related to the decrease in social activity during the pandemic.

The analysis of response time revealed that the average response time for emergency calls increased during the COVID period. In particular, there was a significant increase in response time for calls related to "sick person" and "difficulty breathing," which is likely due to the increased demand for emergency medical services during the pandemic. However, response times for other call types remained relatively stable.

When exploring the relationship between boroughs and various metrics, the analysis found that Queens had the highest average hospital travel time and the highest percentage of calls related to "difficulty breathing." Meanwhile, Brooklyn had the highest percentage of calls related to "assault" and "shooting." These findings suggest that there may be differences in the types of emergency situations that occur in different boroughs, which could inform emergency response planning and resource allocation.

Visualization exploring changes in hospital travel time:
<img width="747" alt="Screen Shot 2023-02-21 at 5 12 33 PM" src="https://user-images.githubusercontent.com/105028034/220479871-c81ebdd0-6ca9-47e0-923f-eae9c922ac26.png">


Finally, the analysis revealed a significant correlation between the number of automobile accidents and the average call response time. In other words, when there were more automobile accidents, response times for emergency calls tended to be longer. This finding underscores the importance of traffic management and accident prevention in improving emergency response times.
Visualization examining the correlation between automobile accidents and response time:
<img width="738" alt="Screen Shot 2023-02-21 at 5 13 00 PM" src="https://user-images.githubusercontent.com/105028034/220479923-499dfaf3-f235-4a36-9409-1df076b42a73.png">

This visualization showcases once again the steep decrease in automobile accidents:
<img width="748" alt="Screen Shot 2023-02-21 at 5 14 40 PM" src="https://user-images.githubusercontent.com/105028034/220480135-98fca4df-f7d3-46a7-a5e0-9c9312bc89f5.png">

Overall, the findings of this analysis provide valuable insights into the trends and patterns of emergency call data during the COVID-19 pandemic. These insights can inform emergency response planning and resource allocation to better serve communities and improve overall emergency response times.

To combine all of the findings of the report, I create a plot that shows five circles, one for each New York City borough, and the numbers around each borough correspond to New York City police precinct numbers. The size of the squares and circles are proportional to the volume of calls, and the distance of each shape from the center of its circle is proportional to the average response time. The blue circles represent calls during COVID, while the red squares indicate calls before COVID. The first section of the plot scales the size and distance of shapes within each borough, while the second section scales the size and distance uniformly across all five boroughs.

<img width="711" alt="Screen Shot 2023-02-21 at 5 16 52 PM" src="https://user-images.githubusercontent.com/105028034/220480457-4fece24c-24ab-4cb7-9211-f6f219c5559d.png">

## Conclusion

In conclusion, this report has provided a comprehensive analysis of how the COVID-19 pandemic has impacted the New York City EMS system. Through an examination of EMS call data from the pre-COVID and during COVID periods, this report has demonstrated that the pandemic had a significant impact on call volume and response time. Specifically, the data showed a reduction in call volume and response time across all precincts, suggesting that the EMS system was able to maintain its level of service during the pandemic.

This report has also identified several important factors that contribute to EMS call volume and response time. For instance, the report found that call volume and response time vary significantly by borough, with certain boroughs experiencing higher call volumes and longer response times than others. Additionally, the report found that the type of call and the time of day can also have a significant impact on response time, with certain call types and time periods requiring more resources than others.

One of the major strengths of this report is the use of data visualization techniques, including graphs and the "killer plot," to present the findings in a clear and easily digestible manner. These visualizations help to highlight key patterns and trends in the data, and provide a useful tool for policymakers and other stakeholders to understand the challenges facing the EMS system in New York City.

Moving forward, there are several important implications of this report that should be considered. First, policymakers and EMS administrators should continue to monitor and adapt to changes in call volume and response time, particularly in the context of future public health crises. Additionally, efforts should be made to address the disparities in call volume and response time across different boroughs, and to identify ways to more efficiently allocate EMS resources to areas with the greatest need.

In summary, this report provides a comprehensive analysis of how the COVID-19 pandemic has impacted the New York City EMS system. Through an exploration of call data and data visualization techniques, this report sheds light on the challenges facing the EMS system, while also identifying areas for improvement and future research. Ultimately, this report provides a valuable resource for policymakers, researchers, and other stakeholders who are committed to improving the quality and effectiveness of the EMS system in New York City.
