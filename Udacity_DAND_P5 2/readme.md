# Data Visualisation with Ford GoBike data
## by Anshul Rampal


## Ford GoBike Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

Each trip is anonymized and includes:

Trip Duration (seconds)
Start Time and Date
End Time and Date
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude
End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
Member Year of Birth
Member Gender

We did data wrangling/cleaning in order to obtain clean data. Null valued records were dropped. Records with  Member age greater than 100 were also dropped. 

New Columns were derived out of existing columns. For instance, member_age was derived from member_birth_year and weekday was calculated from start date.


## Summary of Findings

> After analyzing the start station name and end station name, we got to know that the preferred station was "San Francisco Caltrain Station 2 (Townsend St at 4th St)" . We considered top 20 preferred start and end stations. This could be used for making sure that we have anough bikes as per the demand.

> We identified the age of people who are more likely to book a ride. The analysis showed that people aged 30 are more likely to book a ride. 

> Senior citizens are less likely to book a ride. 

> Maximum number of rides were taken on Wednesday followed by Tuesday. On Saturday and Sunday, less rides were taken. Most people took ride on Wednesday (19%) followed by Tuesday (18.7%) and Monday(18.1%). Least rides were taken on Sunday(7%).

> Male members took more rides as compared to female members and also the bike share for all trip was a little more for male users.

> Subscriber used more rides on Wednesday.

> Mostly people took rides within 400 minutes of duration and also elderly people took shorter rides less than 80 minute duration or even shorter than that.

> Average Trip Duration per user type. Subscriber took shorter duration rides as compared to the customer on an average.

> Female's took longer duration rides than male and others.


## Key Insights for Presentation

> We can easily say that senior citizens are less likely to book a ride. So, above the age of 65, if we think from the company perspective, giving concessions and promotional offers to aged people might help in increasing the number of riders.

> After analyzing the start station name and end station name, we got to know that the preferred station was "San Francisco Caltrain Station 2 (Townsend St at 4th St)" . We considered top 20 preferred start and end stations. This could be used for making sure that we have anough bikes as per the demand.

> Although male members took more rides, female members took longer duration rides.