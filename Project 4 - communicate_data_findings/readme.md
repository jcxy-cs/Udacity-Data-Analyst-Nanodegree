# Ford GoBike Ride Duration Exploration
## by Joel Chua


## Dataset

> The data consists of features of approximately 174,000 rides from the Ford GoBike bike sharing system from the year 2019. There are 15 variables within the dataset, including ride duration, ride start and end time and user demographic info such as user type, gender and birth year. 17536 data points were removed from the analysis due to incomplete or inconsistent data. The data set can be found here: https://s3.amazonaws.com/fordgobike-data/index.html


## Summary of Findings

> During the exploration, surprisingly, age did not appear to affect the ride duration of users. Other features such as gender affected ride duration, but only to a small extend. User type proved to be an interesting feature to explore. Differences were observed in ride behaviours between "Subscribers", who are recurring members of the bike sharing programme, and 'Customers', who are likely one-time users of the service. Generally individual customers have longer ride durations than subscribers. Customers also take longer ride during the middle of the day from 10am to 5pm. Whereas subscribers seem to have very consistent ride durations of around 7 minutes.


## Key Insights for Presentation

> Focusing on the differences in ride usage between customers and subscribers, we first look at a log-scaled distribution of ride durations, noting the unimodal distribution peaking at around 10 minutes. Next, the distribution of user types, which is heavily subscriber favoured (90.2%). To go deeper, we look at the hourly distribution of rides alongside the hourly ride duration for both customers and subscribers. Finally, to round off the exploration, we explore the total hourly bike usage across both subscribers and customers, which reveals the difference in ride behaviour between customers and subscribers as well as interesting changes in usage across weekdays and weekends within both user types. 
