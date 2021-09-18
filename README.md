# Bikesharing Feasibility Analysis
#### Bikesharing in Des Moines, Iowa: as inspired by model deployed in Manhattan, New York

Analyst:
Stan Misina, Columbia University

Data provided by New York Citi Bike System data: https://www.citibikenyc.com/system-data<br />
Analysis is of the month of August, 2019 (201908-citibike-tripdata.csv) - 2,344,224 rides

Software employed:<br />
<i>ETL - Python 3.8, Jupyter Notebook 6.4.1</i><br />
<i>Data Visualization - Tableau Public 2021.3.0(20213.21.0822.2038) 64 bit version</i>

Tableau Public Online publish site: [link to dashboard](https://public.tableau.com/views/TableauChallenge_16317440220100/BikesharingAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link "link to dashboard")

## Overview of statistical analysis
This report is to aid investors in deciding to fund a similar project in Des Moines. We will take a look at average a number of critical data points including anticipated bicycle usage, anticipated rider profiles, usage hours, and more. August 2019 in Manhattan provides a good sample size and transparent data set.

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
Subscriber customer types show a strong usage, indicating that use by the local population is popular. This will make for a cleaner, healthier, and fitter where bikesharing is provided. It would be a consideration for young professionals when selecting a new residence. This can be the catalyst or feature of an emerging alternative fuel movement for Des Moines.<br />
<img width="300" alt="TripsByGenderWeekday" src="https://user-images.githubusercontent.com/84740997/133911064-758c356d-5f92-43c6-9ede-0a2936866d9c.png">

[Average Trip Time by Age](https://public.tableau.com/shared/NPRWT23M8?:display_count=n&:origin=viz_share_link)
Taking into consideration ages 18 to 75, usage trends downward as folks age -- but doesn't ever stop! An average 10-15 minutes is seen well into the customer's 70's. There seems to be an anomoly for people aged 52; however with this data set, we can assume it would fall into a more average time frame of 14-15 minutes.<br />
<img width="1106" alt="AverageTripDurationByAge" src="https://user-images.githubusercontent.com/84740997/133911220-14c71b69-c474-4b6c-923f-e60f9908eb9f.png">



## Summary:

There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)
