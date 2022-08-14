# Bikesharing

## Overview:

The purpose of this analysis is to determine if a Bike sharing program would perform as well in Des Moine, IA, as has performed in New York City, NY.  Using the bike ride data for NYC in August, several visualizations were put together to answer specific questions around trends using Tableau Public.

## Resources:
- Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
- Software: Tableau, Python 3.7.6, Jupyter NB, Pandas Library

## Results:

The results of the NYC Bike Share Analysis ([find it here!](https://public.tableau.com/app/profile/courtney.knittel/viz/bikesharenyc2018/NYCBikeSharingAnalysis?publish=yes)) are on Tableau Public.  

- Looking at visualizations for 'Checkout Times for Users' and 'Checkout Times by Gender', we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour. We also see that this pattern is the same regardless of gender.
- The beginning and ending points are a valuable data set and show that the highest use starting points are also the highest ending locations.  Could there be too few or too many bikes in some of these locations over the course of the day?
- The next visual worksheet in the analysis story shows heavy weekend usage, trends towards the end of the week as well as commute times in the morning and evening bands. Specifically between the hours fo 5am-9am and 4pm - 8pm). It should be noted that Wednesday evenings are not as busy during commute and gives an opportunity to look into other factors with data.
- The next visualization takes the previous one: one step further and breaks the data down into gender usage.  The pattern of usage for commuting and weekends is the same in both genders, and shows the much higher usage of people who have self-identified as "male" vs "female."
- Using another heat map to further the narrative; with usage breakdown by subscriber vs customer, and then gender.  Can we assume subscribers are weekly commuters and customers are tourists?  This would need more data to support this assumption.
- The final story page with two separate visualizations: The Peak Hours with highlighted usage hours, could help determine bike repair times, or relocation to high usaged areas.
The trip by age could help with marketing to generate targeted marketing campaigns.

## Summary:

While this is a great start with data, more is needed for a full analysis.  Looking at some parallels for Des Moine and New York City would be helpful.  How far are the bike starts and stops from each other?  Repeating patterns of weekday usage by user type would be helpful.  It would answer if people are more likely commuting to work, versus tourists using them to get around the city.  Do any of the stop/start locations coordinate with top trouist places?  Does Des Moine also have top tourist areas or a commuting group?  We looked at August, as Des Moine and NYC have winter weather that factors into usage, are these bikes best serviced over the winter and deployed only in the spring, summer, and fall?

Based on the limited data and useful ecplanations with the data visualizations, I would say more data is needed to fully reccomend a Bike share program in Des Moine.  They might be able to run a small pilot program and then compare/contrast the data with some of the trends among user gender, days of the week, and trip duration for both cities.  Des Moine might find that as it is not as large as NYC, the tripduration might be less, but more frequent rentals.
