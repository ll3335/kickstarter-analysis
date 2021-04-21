# Kickstarting with Excel


## Overview of Project
This project is comprised of two analysis: Outcomes Based on Launch Date and Outcomes Based on Goals. We will visualize the relationship between outcomes and launch date as well as outcome and goals in excel to predict the trend.

###Purpose
As the new play Fever comes close to its fundraising goal soon, we want to know how different campaigns fared in relation to their funding goals and launch dates.



## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For Outcomes Based on Launch Date, we use pivot table and graphing in excel to visualize it. It is filtered by Years and Parent Category.The row labels displays the months of the year, and the campaign outcomes are sorted in descending order. The line chart illustrates number of successful, failed and canceled projects by month for theater. We can see it fluctautes across the whole year with the peak near May for both successful and failed outcomes. It has a increase trend for both successful and canceled project from Jan to May and decrease trend from May to Dec. The canceled outcomes remain stable and low across the whole year. Successful outcomes always has the most numbers followed by failed projects and canceled projects. Below is the image for Outcomes Based on Launch Date for Theater.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82549066/115595276-ba5e2380-a2a4-11eb-9a6a-fbea4e7316bf.png)

### Analysis of Outcomes Based on Goals
In excel, COUNTIFS() function is used to collect outcomes and goals data. A line chart is used to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. The overall trend for successful outcome percentage decreases with the dollar range of goal increases from 0 to 45000 and increases after. It decreases first from 0 to 25000, increases from 25000 to 40000, decreases from 40000 to 45000 and increases again. The overall trend for failed outcome percentage increases with the dollar range of goal increases from 0 to 45000 and increases after. It increases from 0 to 25000, decreases from 25000 to 40000, increases from 40000 to 45000 and decreases again. Below is the image for Outcomes Based on Goals for plays.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/82549066/115595673-38bac580-a2a5-11eb-8c1e-04f4f84b7d4a.png)

### Challenges and Difficulties Encountered
When trying to get the number of outcomes based on specific goal range, difficulty of filtering both outcome and subcategory data was found. Then I filtered the outcomes first based on successsful, failed and canceled and create new worksheets for each of the outcomes. At last I use COUNTIFS() function to put "plays" as one of the criteria to get the data. I am still practicing how to filter multiple columns in the same time.



## Results
-What are two conclusions you can draw about the Outcomes Based on Launch Date?
1. According to the graph, successful outcomes are the most across the whole year with failed projects in the middle and canceled projects at least in the theater.
2. The most number of successful outcome in the theater is in May according to the graph.

-What can you conclusde about the Outcomes Based on Goals?
According to the graph, with the dollar range of goal increases, the successful percentage has a decrease trend with "less than 1000" has the most successful percentagen. With the dollar range of goals increases, the failed percentage has a increase trend with "45000 to 49999" has the most failed percentage.

-What are some limitations of this dataset?
The outcome may be related to other factors as well such as sponsors and type of plays.
The year considering is from 2009 to 2017 which is across 8 years that may not indicate the detailed relationships or current sitaution.
The country listed here is limited that may not consider regional factors.
There is no information about the quality of the plays/projects.

-What are some other possible tables and/or graphs that we could create?
1. Pie chart of successful, failed and canceled plays in each month to think which month would be best to launch.
2. Line chart of outcomes vs years
3. Column chart of number of outcomes vs goal ranges
