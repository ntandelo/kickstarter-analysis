# Kickstarting with Excel

## Overview of Project
Client wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using Client dataset, campaign outcomes are analyzed and visualized based on their launch dates and their funding goals.

### Purpose
To analyze campaign success rate based on launch date and funding goals; to evaluate potential future performance based on past performance. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Campaigns failures and successes followed the same trends from January - April and from September - December. However, in the summer months (May - August), successes outpaced failures, starting with a large jump in May.During the May - August range, failures trend line remains mostly flat. Cancelations were mostly minimal, though showed a slight increase in January and decrease in July. No plays were canceled in October. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98437495/151712266-6e930fac-5fe3-44bf-bfd9-f14aa1e9ea2a.png)

### Analysis of Outcomes Based on Goals
Campaign success rates outpaced failure rates in the following cost categories:
* Less than $4,9999
* Between $35,000 and $44,999

Successful outcome percentage is largest for smaller productions ($1,000 - $14,999), though the success rate begins to taper off as early as $5,000. However, within the range of $35,000 to $39,000, successes once again outpace failures. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98437495/151712546-0a6c0b80-7754-4756-ba97-3d3bb47bc556.png)

### Challenges and Difficulties Encountered
This data set presented two challenges:
* Dates were not stored as date values. This was overcome by converting Unix to date values in the data se.

## Results

### Outcomes related to Launch Date
1. Data distribution suggests that campaign success may be correlated with the time of year. Warmer, sunnier months may put the public in a better mood, and they may feel more inclined to donate funds during those months. Additionally, there are no large holidays to compete with (Christmas, New Years, Diwali, etc), which frees up time and money from the public. 
2. Cancelations are a rare event, and do not correlate with success/failure trends. This indicates that play success is largely dependent on goal attainment. 


### Outcomes related to Goals
Relationship between success and failure rate appears mostly inverse. This indicates that there are a finite number of donors, who either do or do not donate. Successful outcome percentage is largest for smaller productions, though the success rate begins to taper off as early as $5,000. However, within the range of $35,000 to $39,000, successes once again outpace failures. This may mean that the perceived quality or popularity of the play may influence donor amount. It could also be influenced by time of year, quality of advertisements, or other external factors. This indicates that donors are more likely to contribute if the goal is smaller, and may seem more attainable. If the goal is too large, donors may feel as though donations are pointless since the goal can never be reached. 

### Dataset Limitations
Data does not include metrics for quality of play advertisement or perceived public perception of the play. These two factors could have a large influence on willingness to donate, especially for larger productions. There does seem to be willingness to donate larger sums of money, however it is not possible with current data to evaluate the true reason. There is also no way to determine which backers donated once, a few times, or regularly. It would be useful to understand which backers donated money frequently, or if there is a time of year when one-time donations spiked.

### Further Analysis
More charts could be produced to further analyze this data, such as:
* Success rate based on countries with harsh winters versus those with a moderate climate
* Success rate of plays based on subject content of play
* Success rate of plays based on advertisement quality
* Count of backers based on month and subject of play

