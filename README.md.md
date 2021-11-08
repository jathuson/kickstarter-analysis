# Kickstarting with Excel

## Overview of Projec

### Purpose
Louise just finished fundraising for her play, Fever, and now she wants to know how different campaigns did in relation to their launch dates and funding goals. In this challenge, the Kickstarter dataset will be analyzed and visualize to address the two insights requested by the client, Louise.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the analysis on the effect of launch date on fundraising performance, the dataset was transformed into a pivot table in Excel. In the pivot table, you are able to filter by parent category and years, with outputs being the count of the different outcomes (successful, failed, canceled) based on month. The fundraisers that were still live were disregarded in the analysis, since it would not be reasonable to include the data from ongoing fundraisers. From the table, a line graph was created with the same filters and outputs. From this graph, the data was represented more clearly. 

### Analysis of Outcomes Based on Goals
For this analysis, I think there were two ways to efficiently populate this data. One method, is two seperate the Goal columns into two columns of min and max, so that when calculating the number of outcomes, they can be easily referenced in the formulas and there would be less room for error. I used this method, but with helper columns so that is more clear. In a real world scenario, these columns can be hidden, so that there is less confusion. Another method, is to use pivot tables and using the function called "Grouping", this allows use to easily build the different groups of goals in a pivot table. One thing to note, is that the groupings would be different in this case, since it would start at 1000 and then go up 5000 for every group, instead of starting at 1000 and going from 1000-5000 and then up by 5000 for each group. I have shown an example in the excel file under the sheet called "Alt. Outcomes Based on Goals". After calculating the number of outcomes for each tier of goals, the total projects were calculated for each and then the percentage was calculated from both those calculations. From there, a line chart was used to visualize the data in a clear and concise manner. The line chart was used because it showed the trend of the outcomes as the goals increased in monetary value.


### Challenges and Difficulties Encountered
I think a potential challenge, is taking into account the cancelled projects, as these projects could have been cancelled for different reasons that do not directly relate to the fundraiser and difficult to predict accurately. Another challenge that I faced was the reptitiveness of the calculations for outcomes based on goals, this could have been done faster with pivot table.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
It was found that the peak time to run a theater fundraiser would be in the month of May, where there were 111 successful campaigns. Compared to the average of approximately 60 in the other months. 

- What can you conclude about the Outcomes based on Goals?
 From the chart, it is clear that the higher the goal was, the less likely the project would be successful and more likely to cancel or fail. Especially when the projects had a goal of higher than $50,000, the project would be more likely to fail or be cancelled than succeed.  

- What are some limitations of this dataset?
One of the limitations of the dataset is that each fundraiser could be skewed from outliers, so having the descriptive statisitcs such as median, mode, IQR, etc, would have helped with a more accurate picture. I think an important factor when it comes to fundraising would have been if what types of marketing or outreach was done for each fundraiser as that can play a role in the amount raised. 

- What are some other possible tables and/or graphs that we could create?
I think a deeper dive into the percentages of each month in the outcomes by launch date would help this analysis and would recommend to Louise to take that extra step.  I do think that there needs to be one more factor that could be analyzed to give a better picture. This factor would be the relationship between the length of a fundraiser and the percentage of the goal that was reached. This would help Louise with determining how long she should run her fundraiser for.  I think looking into the number of backers and the relationship it had with launch date, length of fundraising, and how much fundraised would have helped as well. 