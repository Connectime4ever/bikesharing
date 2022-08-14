# Bike-sharing Program Analysis

## Overview of the analysis
#### The purpose of this analysis is to bring insigths and answer some key questions for better informed decisions in the creation of a bike-sharing program in a selected city. 
#### Tableau is the visualization tool used to perform the analysis, and additionaly a Tableau story was also requested.  
----
## Results
![D11](https://github.com/Connectime4ever/bikesharing/blob/main/D11.png)

Overall, bikes tend to be checked out for less than one hour and more likely between 3 to 11 minutes. 
![D21](https://github.com/Connectime4ever/bikesharing/blob/main/D21.png)
The checkout times by gender follow similar patterns between males and females, and compared to the general performance.
![D22](https://github.com/Connectime4ever/bikesharing/blob/main/D22.png)
From Monday through Friday the highest peaks in the morning hours are at 8 am.  In the afternoon, the highest peaks are recorded from 5pm to 6pm, specially on Mondays, Tuesdays, Thursdays and Fridays. 
Thursdays seems to be the busiest day of all. 
The weekends are more busy from 9am to 5pm on Sundays and to 7pm on Saturdays.
![D23](https://github.com/Connectime4ever/bikesharing/blob/main/D23.png)
It seems females and males follow the same overall pattern. This is much more noticeble in males as they show the highest everyday-trip count, over performing females in a large extend. 
![D24](https://github.com/Connectime4ever/bikesharing/blob/main/D24.png)

Men tend to be dominant in the subscriber category, showing the highest bike use on every weekday. There is no significant pattern in non-subcriber category by gender neither by day of the week in general.
![D25](https://github.com/Connectime4ever/bikesharing/blob/main/D25.png)
It seems men riders tend to have the highest share in the overall bike-sharing program.
![D29](https://github.com/Connectime4ever/bikesharing/blob/main/D29.png)
It seems the bike-sharing category is blooming. There are numerous starting and ending locations and they seem to be at a reasonable distance. The top 10 starting and ending locations seems to be the same.  
![D26](https://github.com/Connectime4ever/bikesharing/blob/main/D26.png)
![D27](https://github.com/Connectime4ever/bikesharing/blob/main/D27.png)
It seems the highest peak hours in August are recorded at 5pm, 6pm and 8am.
![D28](https://github.com/Connectime4ever/bikesharing/blob/main/D28.png)

----
## Summary
### Final Report and Tableau Story. 

- Bikes are tend to be checked out for less than one hour and more likely between 4 to 11 minutes for all riders and genders.
- Users are more likely to check out a bike on Mondays, Tuesdays, Thursdays and Fridays from 6 am to 9 am and from 4 pm to 7pm. Specially on Thursdays. 
- On weekends users are more likely to check out a bike from 9am to 5pm on Sundays and to 7pm on Saturdays.
- Men tend to be dominant in the subscriber category, showing the highest bike use everyday weekday. There is no significant pattern in non-subcriber category by gender neither by day of the week in general.
- The average trip duration by age tends to be higher for youger riders. 
- It seems the bike-sharing category is blooming. There are numerous starting and ending locations and they seem to be at a reasonable distance. The top 10 starting and ending locations seems to be the same.  
 

##### Tableau Story
![D31](https://github.com/Connectime4ever/bikesharing/blob/main/D31.png)
![D32](https://github.com/Connectime4ever/bikesharing/blob/main/D32.png)
![D33](https://github.com/Connectime4ever/bikesharing/blob/main/D33.png)
![D34](https://github.com/Connectime4ever/bikesharing/blob/main/D34.png)
![D35](https://github.com/Connectime4ever/bikesharing/blob/main/D35.png)

#### Visualizations suggested for future analysis. 
+ This visualization below gives a quick and straighforward picture of the most frequent trip durations. Tableau features it can be easily appreciated that the most frequent trip durations are between 3 and 11 minutes and that more than 1 million trips are comprised in this timing range (***49% of the total trips***).  
![D36](https://github.com/Connectime4ever/bikesharing/blob/main/D36.png)
+ Looking at bike use and maintenance needs portion, it might be helpful to group the bikes (bikes Id) based on a classification (bins), so a visualization could be done following that criteria.  For example: heavy use (need maintenance), moderate use, etc., based on the number of trips and weighted by a trip duration.  The data could be group in jupyter notebook before it is loaded in Tableau for visualization. 