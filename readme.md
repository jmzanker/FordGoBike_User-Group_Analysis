# Ford GoBike User-Group Analysis
## by Jochen Zanker


## Dataset

The dataset originates from FordGoBike and contains data of around 2.38 million individual rides. The data covers the time span of June 2017 to December 2018. The dataset includes station names, the user type (subscriber or casual user), gender, user’s year of birth, trip duration, start and end time-stamps, start and end stations coordinates/names, as well as bikes and stations IDs. Each row represents a single ride. This set of attributes allows to base the analysis to the action of a ride. Limitation: A basis on the entity of the user is not possible. The dataset contains "ride-related" and anonymized data only, and includes the following dimensions and metrics:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Member Year of Birth
- Member Gender


## Summary of Findings

The here analyzed dataset from FordGoBike is based on the ride data from June 2017 to December 2018. This period is also the period of observation. The dataset has been explored by segmenting the data using the variables of user type (subscriber or regular customer), gender, age and by quantitate variables such as amount of rides and their duration.

The exploration revealed that most rides have been done by subscribers (84%). Male users account by far for the highest proportion of rides (74%). Female and male users between 25-34 years are the group which used the service most often. Interestingly, rides of female users were done at a younger age compared to male users. The relative distribution of rides shows a higher density around the age of thirty for woman, compared to man. Most rides took less than 40 minutes, whereas rides done by customers have a higher duration than those of subscribers. Visualizations show, that especially younger and male users show very frequent usage behavior, where older users aging between 45-54 years show very low usage. Furthermore, the group of female users shows overall lower usage in terms of amount of rides and total duration, compared to male users. I also observed that the usage in terms of amount of rides and the duration do not diverge much among the segments of age group and gender. That means, the group with most rides also has the highest total ride duration. The same goes for the other segments. The highest usage is achieved by male users between 25-34 years. The second highest by males between 35-44 years. The duration per trip (in the group of subscribers) shows that woman tend to have little longer enduring rides than man. Furthermore, rides of older users tend to endure longer than rides of younger users.


## Key Insights for Presentation

With the presentation I want to describe how user groups of FordGoBike in San Francisco are using the service. It aims to show which segments of users are using FordGoBike extensively and which are not, to identify potential for growth. The segments are defined by the member type (subscriber or cusual user), gender and age.