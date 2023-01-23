# bikesharing

[link to dashboard](https://public.tableau.com/app/profile/jose.ochoa1755/viz/CitibikeNYCAugust2019Analysis/Story1?publish=yes)

## Overview:

The purpose of this analysis was to evaluate the potential of a bike sharing program in Des Moines, IA by analyzing bike trip data from NYC Citibike from August 2019. Using Tableau we  create a set of visualizations that provide insight into the bike trip patterns of different riders and genders.

## Resources:
  * jupyter notebook 6.4.8
  * tableau 2022.4.0
  
## Results:

![Customer Gender](https://user-images.githubusercontent.com/110706169/213993275-7f31e88c-b183-47a4-a351-9ce5aff4a4e0.png)
![Customer Type](https://user-images.githubusercontent.com/110706169/213991618-a0d7cb33-9dff-4ef3-8617-cc3d226e55c6.png)

We found that the majority of our customers are male, accounting for 72.5% of our customer base. Female customers make up 25.5%, while 2% of our customers have an unknown gender. This information can help us understand our customer demographics for marketing purposes. We also found that 81% of customers are subscribed to Citi Bike NYC, while 19% are non-subscribed. This information is valuable as it highlights the potential for growth in the subscriber base and the opportunity to retain and convert more customers into subscribers.

![CheckoutLength](https://user-images.githubusercontent.com/110706169/213991891-45559536-9b37-4194-b17c-ba5414e63ec9.png)

The graph above shows that the majority of our customers, both male and female, tend to have similar checkout duration, with a peak at around 10 minutes. This indicates that the checkout process is efficient and user-friendly for both genders. Additionally, we found that males have a slightly higher number of checkouts at the 10-minute mark, with 108k checkouts, while females have 35k checkouts at the same duration.

![WeekdayPerHr](https://user-images.githubusercontent.com/110706169/213993652-964ab313-1c95-4d47-9757-165f13e5ccb9.png)

![WeekdayHrGender](https://user-images.githubusercontent.com/110706169/213993910-609d3fe5-8423-49f2-8013-d188af75b52c.png)

 The majority of customer usage occurs during the weekdays, specifically on Monday, Tuesday, and Thursday, with peak usage times at 8am and 5-6pm. This information can help us understand our customers' behavior and identify the best times to target  marketing and promotional campaigns. Additionally, when we looked at usage by gender, we found that males make up the majority of that activity during peak hours. This information is valuable because it would allow for a better targeted marketing.

![PeakHrs](https://user-images.githubusercontent.com/110706169/213994033-22efb841-1e28-4c9b-837a-8e375d8a66ee.png)

 From the graph above, we found that the average peak hours of user usage throughout the month of August are between 4 and 7 pm. This confirms the findings from our previous heatmap and can help us optimize our operations by scheduling important tasks such as promotions and marketing during peak hours. The graph also shows that usage is at its lowest between 2 and 4 am. This could indicate an opportunity for maintenance and repairs to be scheduled during these off-peak hours to minimize disruptions to the customers.

 
 ![End Locations](https://user-images.githubusercontent.com/110706169/213994179-9a00c5b9-6b91-488a-986f-682ccfe4c1c4.png)

We found that a high concentration of bike trips end in this specific area of NYC indicating a hotspot for users. This data can help us better understand where to place marketing efforts, potential new stations, and potentially expand the business.

![BikeIDUsage](https://user-images.githubusercontent.com/110706169/213994439-51688222-44c6-4ae2-8aec-99db738d5cfb.png)

This visualization shows bike IDs and their use frequency. By proactively identifying these bikes, we can minimize disruptions to our customers and improve overall fleet efficiency.
Furthermore, this data can also suggest that there is a high demand for specific bikes, which can be used to identify customer preferences and tailor services to better meet their needs.

## Summary:

In conclusion, our analysis has provided insights into customer demographics, behavior, and preferences. We found that the majority of our customers are male, with peak usage times during the weekdays, specifically on Monday, Tuesday, and Thursday. Additionally, we found that 81% of our customers are subscribed to our service, indicating a solid customer base and potential for future growth. We also found that a high concentration of bike trips end in a specific area of NYC, which highlights the potential for targeted marketing and promotional efforts in that area. Lastly, we found that certain bikes are used more frequently than others, which can help us optimize our operations by prioritizing maintenance and repair for high-use bikes.

### Visaulization Suggestions

1. Show usage of customers by day or month to identify trends in customer behaviour. This could help visualize the amount of usage fluctuation in different seasons and weather conditions. 

2. A graph by user age and subscription status would help us identify which demographic are more likely to become subscribers and focus efforts on retention.
