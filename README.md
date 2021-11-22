# Overview of Project
## Purpose of this analysis
The purpose of this analysis is to use Excel for this Kickstarter data set on several thousand crowdfunding projects to uncover trends of the campaigns' outcomes ("successful," "failed," and "canceled") in relation to their launch dates and the funding goal amount which were visualized using Excel. It is to help understand the specific factors that make a project campaign successful by organizing, analyzing, and visualizing this dataset which tells us the outcome or trend and what is required for a successful outcome. 

# Analysis and Challenges
A pivot table was created to depict the Successful, Failed, and Canceled campaigns by the months of the year which was filtered and sorted in asscending order by months to create the line chart below. Thus, this analysis shows the number of campaigns and success rate.
### 1) Analysis of Outcomes based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/33900637/142798072-d55844c0-b68f-40e8-81cb-c54cfe8fe4a7.png)
The COUNTIFS() function was used to group the ranges into Successful, Failed, and Canceled outcomes for the "plays" subcategory and a percentage outcome was calculated for each range.
The chart below was created to visualize which determined whether the Goal values have an impact on outcome.
### 2) Analysis of Outcomes based on Goals
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/33900637/142798200-9105e331-3870-471e-96a3-dd52cb4745e2.png)

From these analayses I found it challenging using a "COUNTIFS()" fuction to populate the number of success, fail and cancel based on the funding goal amount. It was easy to enter the wrong number or type a "<" when ">" was actually intended. It needed to be double checked for accurate results. It was also challenging using pitvot tables since I am unfamiliar and I had to double check which field should go under filters, columns, rows, or values. Overall, the Kickstarter dataset was fairly easy to work with because the instructions were understandable and the data was structured and needed minimal organizing. I overcame all these challenges by looking back at the modules, using the search engine on Excel, and with the assistance of Excel helping me formulate the COUNTIFS(). 

# Results
## Two conclusions about the Theater Outcomes by Launch Date
If we filter for only the "theater" on Kickstarter, we will find that the month of May appears to be the most successful time to launch a theater campaign and the least successful is in December which appears to be the worst time to launch this type of campaign. Also, Kickstarter theater campaigns appear to have a fairly low chance of being canceled and do not seem to depend on the month. Canceled campaigns ranged anywhere from zero to seven occurrences.
## Conclusion about the Outcomes based on Goals
The successful percentage decreases as the funding goal increases, meaning that asking for too much money may fail in fundrasing thus higher the goal, higher chances of failure.
## Limitations of this dataset
The Goal amount and month of the year affects whether a project is successfully funded thus other factors needs to be included in the data set so we can understand how to increase the probability of success.
## Other possible tables and/or graphs that we could create
We could create a line chart by comparing categories, countries, and average donation amounts or a box plot of successfully funded plays in the US. 
