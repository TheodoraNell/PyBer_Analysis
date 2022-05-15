# PyBer Analysis

Performing an analysis on rideshare data using Pandas

## OVERVIEW
The Purpose of this analysis is to explore Q1 data for a rideshare company and identify trends specific to different city types: Urban, Suburban, and Rural. The Summary section provides recommendations on how the company can address disparities among the different city types. 

## RESULTS

![Pyber_summary_df](https://user-images.githubusercontent.com/99051640/168494491-e3b2c758-168a-4d87-b964-ef3fff46069b.png)

### Total Rides

As seen in the dataframe, the number of total rides is highest in urban areas and lowest in rural areas.
**Urban rides: 1,625 | Sburban rides: 625 | Rural rides 125**

### Total Drivers

Like the data for total rides, the number of drivers was also highest in urban areas and lowest in rural areas.
**Urban drivers: 2,405 | Suburban drivers 490 | Rural drivers 78**
It is interesting to note that the number of urban drivers is hihger than the number of urban rides. The reason for this is unknown but it suggests that there are potentially more drivers than the damand requires in urban areas. 

### Total Fares

This metric also continues the trend.
**Urban fares: $39,854.38 | Suburban fares: $19,356.33 Rural fares: $4,327.93** 

### Average Ride Fare

Unlike the other metircs, the average ride fare is lowest in urban areas and highest in rural areas.
**Urban Average Fare: $24.53 | Suburban Average Fare: #30.97 | Rural Average Fare: $34.62**

### Average Driver Fare

Similar to the average ride fare, the average fare per driver is lowest in urban areas and highest in rural areas. 
**Urban Driver Fare: $16.57 | Suburban Driver Fare: $39.50 | Rural Driver Fare: $55.49**

### Total Fare by Week
![PyBer_fare_summary](https://user-images.githubusercontent.com/99051640/168496255-43ead86c-096c-4a63-ac1f-dcfc2cd94208.png)
When veiwed chronologically, The trend continues with Urban ares consistently having the highest total fares and Rural areas having the lowest. However, other trends can also be seen including similarities in increases across all city types during certain weeks (in February for example). It would be interesting to explore possible reasons for these increases (aside from widely celebrated holidays) There is also an apparent general increase in total fares for all city types across the selected time frame. This is likely due to seasonality and invites a deeper exploration into how the time of year affects rideshare demand. 

## SUMMARY

Based on the analysis there are a few recommendations that can be made to separately address disparities among the different city types. 

### Balance the number of drivers

There is an apparent overabundance of drivers in urban areas and an opportunity for more drivers in rural areas. A solution could be to recruit more drivers in rural areas or incentivize some drivers from urban areas to work in them. The average driver fares are hihger in rural areas, meaning the take-home pay per ride for each driver is likely also higher. This can be used as an incentive to attract drivers with fewer, longer, higher-paying trips. Also, urban drivers that may not be getting enough activity might find that the additional travel to rural areas is worth an increase in earnings. 

### Adjust how fare rates are determined

The average fare rate for rural trips is almost $10 higher than suburban trips. It would be interesting to explore data regarding trip duration and distance since this difference in cost could possibly dissuede potential customers in rural areas. If the formula for determining ride fare could be examined and adjusted to make rideshare a more financially viable option and therefore more popoular in urban areas. Also, considering the typical lack of public transporation and taxi service in these areas the demand may still be significant dispite having lower populations. 

### Employ strategy to correspond with seasonal demand

It would be beneficial to conduct a deeper exploration of chronological data to pinpoint specific weeks or dates that see an increase in total fares. Increases and decreases specific to one specific city type (as well as across all types) can provide insight into where more drivers might be needed or how fares can be adjusted to increase demand for rides or maximize an already high demand. 
