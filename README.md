# kickstarter-analysis

Written Analysis of Theatre Outcome vs. Launch Date and Goal

1) Overview of Project

The purpose of the project was to analyze raw data of numerous theatre performances. I correlated the outcomes of the performances to the month in which they were released. 
I also correlated the outcomes of the performances to the amount pledged  

2) Analysis and Challenges

In the first part of the project, I created a pivot plot to filter theatre outcomes to the month in which they were released. I then created a graph to visually show this correlation . In the 2nd part of the assignment, I used the raw data to figured out what percentage of the projects which were successful, failed, or canceled. I then created another graph showing outcomes based on goal.
The main challenge I had was converting the UNIX timestamps to regular dates. I overcame this challenge by reading the Excel documentation to solve and overcome this issue 
 
3) Results

As seen in graph named "Theatre Outcomes vs. Launch", we can conclude that most performances are successful in the month of May. We can also conclude that number of canceled performances is relatively consistent throughout the year.
As seen in graph named "Outcomes vs. Goals", we can conclude that percentage of successful performances increases with increasing goal.

One limitation to this dataset is it doesn’t show us the degree to which a performance is successful vs. failure. For example, if the goal is $10,000 and the pledged amount is $10,001, the data simply categorize it as a successful performance. If the goal is $10,000 and pledged amount is $9,999 it is categorized as a failed performance. I would like to figure out the degree to which the performances are a success vs failure by calculating the percentage by which it ha. I would also like to analyze the performances by the year in which they were released as opposed to just the month 

