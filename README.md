# Bikesharing Feasibility Analysis
#### Potential of bikesharing in Des Moines, Iowa: as inspired by CitiBike model deployed in Manhattan, New York

Analyst:
Stan Misina, Columbia University

Data provided by CitiBike System of New York City: https://www.citibikenyc.com/system-data<br />
Analysis is on the complete dataset captured in August, 2019 (201908-citibike-tripdata.csv) - **<i>2,344,224 rides</i>**

Software employed:<br />
<i>ETL - Python 3.8, Jupyter Notebook 6.4.1</i><br />
<i>Data Visualization - Tableau Public 2021.3.0(20213.21.0822.2038) 64 bit version</i>

Published online at Tableau Public: [link to dashboard](https://public.tableau.com/views/TableauChallenge_16317440220100/BikesharingAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link "link to dashboard")


## Overview of statistical analysis
This report is a reference for investors when consideration of funding a similar project in Des Moines. We will take a look at average a number of critical data points including anticipated bicycle usage, anticipated rider profiles, usage hours, and more. August 2019 in Manhattan provides a good sample size and transparent data set of a major metropolitan area in a popular time of year.


<<<<<<< HEAD
## Results:
[Average Ride Duration](https://public.tableau.com/views/TableauChallenge_16317440220100/BikesharingAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
The bike sharing service in NYC is very popular. In the month of August, 2019 alone there were 2,344,224 rides logged on Citi Bike bicycles. Most rides only last 5 minues between stations, however there were longer and longer average rides that numbered into the tens of thousands. For example, 66,769 rides lasted 15 minutes, and 21,346 lasted 30 minutes.<br />
<img width="450" alt="CheckoutTimes" src="https://user-images.githubusercontent.com/84740997/133910624-3f87d3f8-97b4-4cf2-95d6-0989072e8597.png">

[Average Ride Duration by Gender](https://public.tableau.com/shared/R9GCGD3BQ?:display_count=n&:origin=viz_share_link)
To inspect how genders use this service, we can have a look here. The majority of bike share customer are Male by better than a 3 to 1 ratio when compared to Female usage.<br />
<img width="450" alt="CheckoutTimesByGender" src="https://user-images.githubusercontent.com/84740997/133910758-c05e16d7-40b9-4d98-bd22-a3aa38c6aed1.png">

[Trips by Weekday and Hour](https://public.tableau.com/shared/8Z5W3DRKD?:display_count=n&:origin=viz_share_link)
Considering highest usage times, predictably work commuting hours of Monday - Friday 7AM to 9AM and 5PM to 7PM are most active with steady usage throughout the daylight hours on Friday, Saturday, and Sunday.<br />
<img width="450" alt="TripsWeekdayHour" src="https://user-images.githubusercontent.com/84740997/133910876-2cbaa081-97cc-4a2b-be7e-aa6798c474b5.png">

[Trips By Weekday and Hour by Gender](https://public.tableau.com/shared/4TXWKSSWF?:display_count=n&:origin=viz_share_link)
When opening the weekday and hour usage, again you will see here that Male usage of the service is predominant. However, usage times and days are similar -- and nearly identical on weekends.<br />
<img width="900" alt="TripsByGenderWeekdayHour" src="https://user-images.githubusercontent.com/84740997/133911058-07435dae-7d8e-4e38-97aa-543905f79570.png">

[Usage per day by Gender, Weekday, and Customer Type](https://public.tableau.com/shared/H7YKYB2P3?:display_count=n&:origin=viz_share_link)
Subscriber customer types show a strong usage, indicating that use by the local population is popular. This will make for a cleaner, healthier, and fitter environment where bikesharing is provided. It would be a consideration for young professionals when selecting a new residence. This can be the catalyst or feature of an emerging alternative fuel movement for Des Moines.<br />
<img width="300" alt="TripsByGenderWeekday" src="https://user-images.githubusercontent.com/84740997/133911064-758c356d-5f92-43c6-9ede-0a2936866d9c.png">

[Average Trip Time by Age](https://public.tableau.com/shared/NPRWT23M8?:display_count=n&:origin=viz_share_link)
Taking into consideration ages 18 to 75, usage trends downward as folks age -- but doesn't ever stop! An average 10-15 minutes is seen well into the customer's 70's. There seems to be an anomoly for people aged 52; however with this data set, we can assume it would fall into a more average time frame of 14-15 minutes.<br />
<img width="600" alt="AverageTripDurationByAge" src="https://user-images.githubusercontent.com/84740997/133911220-14c71b69-c474-4b6c-923f-e60f9908eb9f.png">

[Bike Utilization](https://public.tableau.com/shared/WKXB88SFN?:display_count=n&:origin=viz_share_link)
=======
## Results
[Average Ride Duration](https://public.tableau.com/views/TableauChallenge_16317440220100/BikesharingAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)<br />
The bike sharing service in NYC is very popular. In the month of August, 2019 alone there were 2,344,224 rides logged on Citi Bike bicycles. Most rides only last 5 minues between stations, however there were longer and longer average rides that numbered into the tens of thousands. For example, 66,769 rides lasted 15 minutes, and 21,346 lasted 30 minutes.<br />
<img width="450" alt="CheckoutTimes" src="https://user-images.githubusercontent.com/84740997/133910624-3f87d3f8-97b4-4cf2-95d6-0989072e8597.png">

[Average Ride Duration by Gender](https://public.tableau.com/shared/R9GCGD3BQ?:display_count=n&:origin=viz_share_link)<br />
To inspect how genders use this service, we can have a look here. The majority of bike share customer are Male by better than a 3 to 1 ratio when compared to Female usage.<br />
<img width="450" alt="CheckoutTimesByGender" src="https://user-images.githubusercontent.com/84740997/133910758-c05e16d7-40b9-4d98-bd22-a3aa38c6aed1.png">

[Trips by Weekday and Hour](https://public.tableau.com/shared/8Z5W3DRKD?:display_count=n&:origin=viz_share_link)<br />
Considering highest usage times, predictably work commuting hours of Monday - Friday 7AM to 9AM and 5PM to 7PM are most active with steady usage throughout the daylight hours on Friday, Saturday, and Sunday.<br />
<img width="450" alt="TripsWeekdayHour" src="https://user-images.githubusercontent.com/84740997/133910876-2cbaa081-97cc-4a2b-be7e-aa6798c474b5.png">

[Trips By Weekday and Hour by Gender](https://public.tableau.com/shared/4TXWKSSWF?:display_count=n&:origin=viz_share_link)<br />
When opening the weekday and hour usage, again you will see here that Male usage of the service is predominant. However, usage times and days are similar -- and nearly identical on weekends.<br />
<img width="900" alt="TripsByGenderWeekdayHour" src="https://user-images.githubusercontent.com/84740997/133911058-07435dae-7d8e-4e38-97aa-543905f79570.png">

[Usage per day by Gender, Weekday, and Customer Type](https://public.tableau.com/shared/H7YKYB2P3?:display_count=n&:origin=viz_share_link)<br />
Subscriber customer types show a strong usage, indicating that use by the local population is popular. This will make for a cleaner, healthier, and fitter environment where bikesharing is provided. It would be a consideration for young professionals when selecting a new residence. This can be the catalyst or feature of an emerging alternative fuel movement for Des Moines.<br />
<img width="300" alt="TripsByGenderWeekday" src="https://user-images.githubusercontent.com/84740997/133911064-758c356d-5f92-43c6-9ede-0a2936866d9c.png">

[Average Trip Time by Age](https://public.tableau.com/shared/NPRWT23M8?:display_count=n&:origin=viz_share_link)<br />
Taking into consideration ages 18 to 75, usage trends downward as folks age -- but doesn't ever stop! An average 10-15 minutes is seen well into the customer's 70's. There seems to be an anomoly for people aged 52; however with this data set, we can assume it would fall into a more average time frame of 14-15 minutes.<br />
<img width="600" alt="AverageTripDurationByAge" src="https://user-images.githubusercontent.com/84740997/133911220-14c71b69-c474-4b6c-923f-e60f9908eb9f.png">

[Bike Utilization](https://public.tableau.com/shared/WKXB88SFN?:display_count=n&:origin=viz_share_link)<br />
>>>>>>> e8262bd51f126d93c98cfa126580c115a24055f7
Use of individual bicycles is very well spread out over the month. There are individual bikes that are used more than others, however usage is generally evenly allocated. This will mean less downtime for your fleet and should be featured as being highly reliable.
<img width="600" alt="BikeUtilization" src="https://user-images.githubusercontent.com/84740997/133911473-f98f1342-a146-4a1d-bc58-fabae85a71dc.png">


<<<<<<< HEAD
## Summary:
Bike sharing is a popular means of getting around in a city. Locals can use it for commuting to work and attending attractions as a healthy alternative to buses and trains. This helps alleviate public transportation, cars off of congested roads, promotes excercise, and well being. As men are the predominant users of bike sharing, advertising can be targeted at men -- however, women consistently use the service -- especially on weekends. Taking a second look at the Manhattan model, I would recommend comparing another month (e.g., June 2019) and a YTD comparison (September 2018 to August 2019) to consider samples from other times of year, or how the service is used year-round.
=======
## Summary
Bike sharing is a popular means of getting around in a city. Locals can use it for commuting to work and attending attractions as a healthy alternative to buses and trains. This helps alleviate public transportation, remove cars from congested roads, promotes excercise, and well being. As men are the predominant users of bike sharing, initial advertising can be targeted at men -- however, women consistently use the service as well -- especially on weekends. Taking a second look at the Manhattan model, I would recommend comparing another month (e.g., June 2019) and a YTD comparison (September 2018 to August 2019) to consider samples from other times of year, or how the service is used year-round.  

Since CitiBike is transparent with customer data measures, a multi year lookback is possible, and would be valuable as well.
>>>>>>> e8262bd51f126d93c98cfa126580c115a24055f7
