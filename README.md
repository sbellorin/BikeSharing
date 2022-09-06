# BikeSharing
#### *Created a story and multiple dashboards to analyze and visualize citi bikes data using Tableau and Python*

## Overview
This project consisted on creating a pitch for a citi bike (bikesharing) business proposal for angel investors looking to seed fund. The goal was to look at citi bike data in New York City on the month of august to look how this bikesharing business operates in its prime during summer. After analyzing the data and cleaning it up a bit, I then created visualizations to display the trends and opportunities it would have in other cities. 


## Resources
- Dataset
  - Download the `201908-citibike-tripdata.csv.zip` from this [CitiBike link](https://s3.amazonaws.com/tripdata/index.html) 

- Software
  - Python
  - Pandas Library
  - Tableau Public

## Results
[Tableau Public Story](https://public.tableau.com/app/profile/juan.nicolas.serrano/viz/CitiBikeProposal_16288132514370/Story1?publish=yes)

This presentation was based on New York City but could be applied, with the necessary attention, to other cities in the World. 

![Screen Shot 2021-08-13 at 3 31 27 PM](https://user-images.githubusercontent.com/83378141/129409815-46ddecae-7a28-4507-92f2-a72d5fb0689c.png)

During august, the most profitable month of the year, the most popular hours in which people used the bikes were 5 and 6 pm during the afternoon and 8 am during the morning. This uncovers the trend that people usually use it to mobilize to and from their jobs as the peak hours are before and after work time. 

![Screen Shot 2021-08-13 at 3 31 37 PM](https://user-images.githubusercontent.com/83378141/129410295-ff53dad4-353a-4309-aed6-88380c291778.png)

Moreover, this heatmap supports this theory as it displays how the most heated and popular times are 8am and 5-6 pm during workdays. It provides additional information such as that thursday is the most popular day of the week, and that saturday and sundays' afternoons are also very popular for bikesharing. 

![Screen Shot 2021-08-13 at 3 31 52 PM](https://user-images.githubusercontent.com/83378141/129411216-12d53132-f023-4752-9447-69d6738d3e14.png)

As it can be seen in the *User Trips Dashboard*, almost 80% of the users are subscribers, meanwhile the others are just customers who sometimes use the bikes. This means that user retention is pretty high and wherever the bikesharing business is created we should strive to give incentives for customers to become subscribers. More specifically, male subscribers are the most popular users followed by female subscribers. There are also many customers who happen to avoid the gender selection, so they appear as unknown gender. We should try to engage more customers as a whole. 

![Screen Shot 2021-08-13 at 3 32 04 PM](https://user-images.githubusercontent.com/83378141/129412450-b3f1a2ef-6562-4a3d-983f-c28f1527b368.png)

In this worksheet, we can see the trip duration by gender. As it can be seen, all genders usually use the bikes for 5 minutes approximately. After 5 minutes, the trip durations start to slope down. Almost nobody uses the bikes after 45 minutes, where the slope starts to decline by a lot. 

![Screen Shot 2021-08-13 at 3 32 31 PM](https://user-images.githubusercontent.com/83378141/129424212-9b8d76f8-f8d7-4905-af52-7d3f77dd8450.png)

Here we can see the gender breakdown, which shows that the majority of customers are male with approximately 65% market share, then women with 25%, and finally unknown gender with 10%. They all happen to have the same heatmap which shows how they have the same behavior on using bikes at the same times (8am and 5-6pm for the most part). 

![Screen Shot 2021-08-13 at 3 32 42 PM](https://user-images.githubusercontent.com/83378141/129426931-d140ac20-6871-4dad-8339-6e5791661daf.png)

And last but not least, we can see NYC's start and end trip spread. Even though this is the map for New York City, we can expect a similar behavior in other cities. There is always a more populated area (in this case Manhattan), where the majority of the bikes would be used. But in general, we can expect a very spread out utilization with full coverage. If possible, we could even provide price incentives for less populated areas. 

## Summary

To further analyze the citi bike business proposition, we created one more visualization in which we observed rides by age. To calculate age I created a Tableau calculated field in which I used the date of birth to get the age. As it can be seen, users have to be 18 years old in order to be able to use the bikes. Also, there is a outlier at 52 years old for 'unknown' gender with over 200,000 rides, which we would have to further investigate because it might be affecting our findings.

![Screen Shot 2021-08-21 at 12 28 34 PM](https://user-images.githubusercontent.com/83378141/130328555-d36533e4-57af-45f7-9802-a491b60f291a.png)

And last but not least, another interesting metric to analyze could be if users use the bikes for daily commutes, leizure, or just rarely. This data could then be used to engage more customers or even convert customers into subscribers. We could then analyze it by gender, age, or other metrics to understand better our market. 
