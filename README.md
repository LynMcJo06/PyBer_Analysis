# PyBer_Analysis
Module 5 PyBer with Matplotlib
In this module, I will be creating visualizations of rideshare data for my company, PyBer.  The goal is to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.  I will be using the Python graphing library called Matplotlib and other libraries to perform my analysis.  Our CEO is V. Isualize and my supervisor is Omar.  
## Lesson 1
I learned how to create line, bar, scatter, bubble and pie charts using both the MATLAB and Object-Oriented Approach (OOP).  After completing the skill drill for the OOP, the coursework asked that I comment on the chart I thought best for graphing the ride-sharing data.  I feel the horizontal bar best depicts the data; I find bar charts easy to read and interpret in a short amount of time.  At the end of the lesson, I learned how to add error bars to line and bar charts, change major tick marks, and add minor tick marks.  In the last exercise, I created graphs for a small dataset.  I did fine until the final skill drill and I could not get error bars added to the bar chart.  I checked the instructor's speed run video and he too could not get the error bars on the chart.  He moved on and so did I.  I should mention that I made several attempts to add the error bars and spent approximately two hours on the skill drill.  
## Lesson 2
I imported and inspected two CSV files and converted them to dataframes.  After verifying that each dataframe looked good and did not have any missing data or need additional cleaning, I merged the two dataframs into one dataframe.  
## Lesson 3
I created dataframes for each city type:  urban, suburban, and rural.  I used the Pandas "mean()" method to get the average fare for each city.  To calculate the number of rides for each city, I used the Pandas "count()" method for each city.  I needed to make the bubble size correlate to the number of each driver for each city by getting the average driver count.  I also needed to create a Series; therefore, I used the Pandas "groupby()" function to get a Series for each city type. Next, I chained the "groupby()" function with the "mean()" method to get the fare averages.   As a final step in preparing the data, I chained the "groupby()" function with the "mean() of the driver count to get the average number of drivers for each city type.  It was time to create the Bubble Charts.  I used the company's color scheme for each city type.  After creating the individual bubble charts, I combined the code into one chart, and added a title, axis labels, a legend and a text label for visual enhancement.  
## Lesson 4
Lesson 4 was all about statistics and creating visualizations.  I created box and whisker plots for ride count data, ride fare data, and driver count data.  The plots showed that urban and suburban have approximately three and a half to four times more riders than rural.  The first plot for urban ride counts had one outlier, which was later removed from the analysis.  Additionally, the plots for ride fare data showed that rural passengers pay between $4.00 to $10.00 more per ride than suburban and urban, respectively.  The final analysis on driver counts showed that rural cities have significantly fewer drives than urban and suburban cities.  
## Lessons 5, 6 and 7
In these lessons, I created three pie charts showing the percentage of total fares by city type, the percentage of total rides by city type, and the total drivers by city type.  Urban accounts for 63% of total fares while suburban and rural account for 30% and 7%, respectively.  For the Percentage of Total Rides by City Type, Urban makes up 68% versus Suburban and Rural at 26% and 5%, respectively.  The last pie chart represented Percentage of Total Drivers by City Type.  Urban accounts for 81% of the drivers versus Suburban and Rural at 17% and 3%, respectively.  
'------
# **MODULE 5 CHALLENGE**
##  **Analysis Overview**
After presenting the previously-mentioned results, the CEO wants a summary of the ride-sharing data by city type, placed into a multiple-line graph.  The multiple-line graph needs to display the total weekly fares for each city type.  As previously stated, the goal is to gather information to assist decision-makers in improving access to ride-sharing services and determining affordability for underserved neighborhoods.  
##  **Results**
### Deliverable 1
The total rides for Urban, Suburban, and Rural were 1,625, 625, and 125, respectively.  Urban has 13 times more rides than rural and approximately two and half times more than Suburban.  The total drivers for each city type are: 2,405 Urban, 490 Suburban, and 78 Rural.  Urban has almost 31 times more drivers than Rural, and five times more drivers than Suburban.  The revenue from fares for 2019 was $4,328 Rural, $19,356 Suburban, and $39,854 Urban.  Urban accounted for nine times more fare revenue than Rural and two times more than Suburban.  The average fare per ride was $24.53 Urban, $30.97 Suburban, and $34.62 Rural; the average fare on rural routes is approximately $10 more than the average fare for an urban route.  The average fare per driver was $16.57 Urban, $39.50 Suburban, and $55.49 Rural--that is approximately three times more than urban.  
### Deliverable 2
The multiple line plot was created for the time frame January 1, 2019 through April 29, 2019, on a weekly basis.  Once again, Urban had the highest total fares for this time frame.  The maximum total fares occurred as follows:  
-   Urban       week ending March 10, 2019      $2,470.93
-   Suburban    week ending February 24, 2019   $1,412.74
-   Rural       week ending April 7, 2019         $501.24  

All three city types incurred a spike in total fares for the week ending February 24, 2019, after which, all three experienced declines in total fares until March.  Suburban ended April 2019, with its second highest total fares of $1,357.75.  
##  **Summary and Recommendations**
Based on the results, I make the following recommendations to address the disparities among the city types:  
1.  Consider increasing the number of routes for rural and suburban, especially during peak time frames.  A cost-benefit analysis should be performed.  
2.  Consider lowering the fares in the rural routes.  
3.  Provided further financial incentitives for rural route riders such as half-off time frames, etc.  
4.  Work with local leaders in suburban and rural areas to enhance ridership.  The more convenient, the more likely someone is to ride.  
5.  Meet with nonprofit groups and community services to brainstorm additional incentives.  

##  Closing
I appreciate the opportunity to provide these analyses and look forward to future projects.  I appreciate and welcome all feedback regardin this matter.  

    
