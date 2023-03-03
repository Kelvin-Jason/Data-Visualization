# (Ford Go bike system)
## by (Kelvin Jason)


## Dataset

The Ford GoBike system Data contains information about the individual rides made in the bike sharing system. 

The data has 183412brows and 16 columns.

I first gathered the data by importing it in the jupyter notebook and then performed some assessing.

From the assessment, I noticed that some columns had missing data while some had the wrong data type.

I therefore cleaned up these issues by filling in the missing values with the mode (most repeated) value, for example, the gender column had 8265 nulls and I filled this with the mode.

The data is now ready for exploration!

From this data, we may need to understand when most trips are taken and what may be influencing the number of trips taken at a certain time and during certain conditions.


## Summary of Findings

*The summary of the findings are as below:*

The top 10 duration time forms a uniform distribution with most of the values being around 280 seconds.

There are more men users than any other gender. The 'other' gender had the least number of users.

We note that most users were subscribers. Actually, over 88% of the users were subscribers while only 11% were customers. I am planning to use this in the explanatory visualization.

Most of the users have age of between 30-40. The age distribution is skewed to the right. This means that the older ages had fewer number of people.

Most of the users preferred weekdays with the most common day being Thursday. Fewer users preferred weekends. I am planning to use this in the explanatory visualization.

The most common start station was Market St at 10th St while the most common end station is San Francisco Caltrain Station 2

The most common bike id was 4794.

Most of the bike ids took very minimal time, while there were some who took upto 80000 seconds. We notice that bike id 4794, most of the time taken by users did not go past 40000

Men were most users across all days of the week. It is noted that as the number of men increased, the number of female also increased. The reverse is also true. I plan on using this visual in the explanatory analysis.


## Key Insights for Presentation

The main insights were:
1. Most of the users were subscribers and not customers.
2. The rides were mainly done during weekdays.
3. Generally, the number of male users were more than the other gender categories.

