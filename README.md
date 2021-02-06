# Bikesharing
To use Tableau to analyze bike sharing dataset (August 2019) obtained from NYC Citibike. 

[link to NYC citibike tableau story](https://public.tableau.com/views/NYCCitibikeChallenge_16126364949790/NYCCitibikeStory?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)

### Overview of the Bikesharing Analysis

The purpose of this work / challenge is to use Tableau to analyze data and generate useful visualization from the bike sharing dataset (August 2019) obtained from NYC Citibike. The outcome of this analysis will then be used to put together a solid proposal for some Angel Investors that are willing to provide seed funds for the set-up of a similar bike sharing business in Des Moines. This work also invoved;

  1. Using Pandas to convert the trip duration column in the Citibike dataset from integer to datetime datatype
  2. Showing the length of time that bikes are checked out for all riders and genders
  3. Showing the number of bike trips for all riders and genders for each hour of each week
  4. Showing the number of bike trips for each type of user and gender for each day of the week
  5. Creating a story and report from the above visualizations for the final presentation and analysis to pitch to the investors

To generate these analysis, I utilized the following resources;

  - Data Source: 201908_citibike_tripdata.csv from NYC Citibike System website 

  - Softwares: Python, Jupyter Notebook, Tableau

  ### Result of the Story Visualization

  The following points enumerate the result of each visualizations that were incorporated into our Citibike story;

   - **Citibike By Usertype & by Gender** - This pie chart visualization from our story is designed to succintly provide useful insight about the overall customer base, customer type and gender distribution of citibikers to the investors. The result shows that Citibike has a total of 2.344m users as at the reporting period. Based on usertypes, 81% are subscribers & 19% are customers. Based on gender distribution, 65% are male, 24% female and 11% unknown.


   - **Trips By Weekday Per Hour** - This heatmap is designed to show our investors an insight into the numbers of trips embarked on by citibikers each hour for everyday of the week. The essence is to enable us understand peak hours for different days of the week to enable us plan and ensure that adequate numbers of bikes are made available to riders. From the heatmap, we could see that the hours between 7am to 9am & 5pm to 7pm are the busiest hours of the weekdays whilst weekends are relatively very light in terms of trips embarked on by Citibikers. Peak trips of about 36,500 trips were recorded at 8am on Thursday & about 44k and 45k trips also recorded at 5pm and 6pm respectively same day


   - **Trips By Weekday Per Hour By Gender** - Having earlier shown our investors the gender distribution of Citibikers and also provided insights into the breakdown of trips per hour, this heatmap was included in our story to further provide insights to the gender distribution of the hourly trips embarked upon by Citibikers. The result shows that the highest number of trips for the male, female and unknown genders occured on Thursday. For males, peak trips of over 25k were recorded on Thursday at 8am and over 35k trips at 5pm and 6pm respectively same day. For the female gender, close to 10k peak trips were recorded at 8am on Thursday and more than 11k trips at 6pm same day. For the unknown gender, peak trip of about 6k trips occured at about 12 mid-day, a deviation in terms of timing from those of the male and female gender 


    - **User Trips By Gender By Weekday** - This visualization in our story aims to provide further insight to the total number of daily trips by gender & usertype combined. The result effectivey showed that the peak total number trips of about 259k trips occured on Thursday by the Male Gender category. For the Female, the peak number trips of about 88k also occured on Thursday. In contrast, the lowest number of daily trips occured on Sunday by the Unkown Gender category


    - **Checkout Times For Users** - This visualization in our story provides our investors with an insight to the distribution of the checkout times / trip durations (in minutes). The result from the graph showed that in the period under review, the most frequent trip duration was for 5 minutes, which occured 146,752 times.


    - **Checkout Times By Gender** - This visualization in our story further dissects the earlier graph of checkout times for users by providing us with the gender distribution of the checkout times. Again, the result showed that 5 minutes was the most frequent which occured 108,087 times for the male gender, followed by 6 minutes for the female gender which occured 34,151 and 11 minutes for the unknown gender which occured 7,389 times. 



    ### Summary

    The following are the summary of my deductions from the results;

    _1. The gender distribution amongst Citibikers is significantly skewed towards the male gender (65%) compared to 24% and 11% for the female and unknown gender respetively. This could be an indication that males are fitter and more favorably disposed to use alternative manual transport system of this nature. From a business perspective, more awareness and incentives may be required to specifically target the female and unknown gender categories_

    _2. Trips By Weekday Per Hour / By Gender - From the results of these 2 heatmaps, we could conclude that peak period for bike rides generally occur on Thursdays for the dominating gender types (male & female) and these periods are between the hours of 7am to 9am and 5pm to 7pm. This could be an indication that most of the bikes are used for commute to and from work by most users._

    _3. User Trips By Gender By Weekday - Flowing from point 2 above where we deduced that most people may be using the Citibikes to commmute to and from work and where we also concluded that peak period was on Thursday, the result of the user trip by gender supported this assumption as we found that users under the category of "Subscriber" carried out the most trips. A subcriber will usually be resident in the city (not a tourist) and will probably be the most likely person to use bikes to commute to and from work at those peak hours that we identified in point 2 above._

    _4. Checkout Times For Users & By Gender: Flowing from point 1 above where we found that males are the dominating gender of the 3 gender types, the result of these charts, where the male gender was observed to have carried out the most trips (108,087 out of a total of 146,752) of the most frequent trip-duration of 5 minutes is a reflection of the gender distribution of Citibikes user base which is in favor of males._ 


 In conclusion and drawing learning points from the Citibike dataset that we have analyzed above, my recommendation for the proposed bike-sharing business in Des Moines is that it should be targeted significantly at residents who most likely will be subscribers. In addition, special incentives may be considered for females and unknown genders to endear them to consider bikes as viable alternative means of transport.     
 
 Two other visualizations that could also be considered given the dataset that we have are;

  _- Scatter plot - which could also be used to show the relationship between trips by weekday per hour._ 

  _- Histogram - which could allow us to group trip durations into bins and plot this against the number / count of trips (number of bikes)._   