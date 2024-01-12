# (Dataset Exploration Title)
## by (your name here)


## Dataset
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area .
The dataset consists of 183412 rows across 16 columns(features). It shows 8265 null values under columns member_gender and member_birth_year, also 197 nulls in columns start_station_id,start_station_name,end_station_id and end_station_name.
I dopped non essential features and null values from the dataset to minimize any noise.

## Summary of Findings

Since the trip duration has a close relationship with bike share company's revenue, I tried to find out what are the key factors affecting trip duration. It turns out that station id or latitude do not have a big effect on the trip duration but user type does have an impact on trip duration. According the analysis, I found subscribers tend to rent the bikes for longer trips. One possible way to increase revenue is to attract more potential customers and convert more exiting customers to subscribers.Also gender has impact as I found females tend to rent bikes for longer durations. Attract more males to have longer trips is a potential way to increase the revenue as males tend to rent more bikes than females.
Users rent bikes over the weekend tend to have longer trip duration than trips booked during other weekdays.

## Key Insights for Presentation

For the presentation, I focus on just the influence of the user type and weekday.
and leave out most of the intermediate derivations. I start by introducing the
trip duration, followed by the pattern in gender, usertype and weekday distribution, then plot the
transformed scatterplot.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the scatter plot of weekday and usertype vs trip duration. I'm only looking at
the user type plot here since it's the clearest example of how user type affect trip duration.
Afterwards, I studies trip duration vs gender and weekday, here I focus on the affect of gender on trip duration.