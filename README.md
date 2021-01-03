# Kickstarting with Excel



## Overview of project
The purpose of this analysis is to provide Louise with readable documentation to gain insight on how different campaigns fared in relation to their launch dates and their funding goals. 


### Purpose

Louise play  **Fever** reached the goal on a short amount of time, Louise wants to understand the elemets that play a significant role on determing the success or failure of a compaign. This analysis will shed light on how some factors contribute to success or failure to a compaign such as when to launch a compaign,the bakers preferences and countries that get the most funds. Using this kickstarter dataset will help deliver outcomes in respect of Louise needs.
Included the source of this dataset [here](/Kickstarter_Challenge .xlsx.zip)



## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

To visualize campaign outcomes based on Launch date, a pivot table and graphing were created based on kickstarter worksheet, applying the following fields :

*Parent category and years in filter

*Outcomes in the columns

*Outcomes in the Values

*Date created conversion in Rows

*the parent category is filtred on theater

*The row labels are changed to display the months of the year, and the campaign outcomes are sorted in descending order

*A line chart is created showing the number of successful, failed, or canceled projects by month

here is the graphic that shows the successful, canceled and failed campaign based on the month of launch, best time to launch fundraising is between Apil and August.


![here](/resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

For this analysis we used the function COUNTIFS to visualize  the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis, applying the following fields:
* Goal, Number Successful,Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed and Percentage Canceled in columns 
* Amount ranging between less than 1000 and greater than 50000 in rows so  so projects can be grouped based on their goal amount

The formula for the Countifs is : =COUNTIFS(kickstarter_challenge!D:D, "<=1000", kickstarter_challenge!F:F,"successful",kickstarter_challenge!R:R,"plays")


![here](/resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

I encountered some difficulties producing some visualizations because of my lack of knowledge in excel but the extra sessions with the assistant teacher helped me solve my issues, also had hard time getting familiar with github. 



## Results


### What are two conclusions you can draw about the Outcomes based on Launch Date?

The graphic Outcomes by Launch Date shows that most successful projects are launched in May and June, May being the pick month, two factors explains this trend the weather and the end of tax return, as the weather get nicer people tend to be more joyful and more willing to put money in fundraising especially after getting some tax return.
Also to note that December is the worst month to launch a project as the failed and successful project tends to be in same level thats because of christmas, people tends to spend a lot of money during christmas.

### What can you conclude about the Outcomes based on Goals?  

The dateset shows that there is a higher probability of successful projects lower the goal is however there is higher probability of successful funding projects with a goal between 20000 and 35000 and projects above 40000.
this might lead Louise to conclude that for smaller project it might be neccessary to try attracting a type of range of the population people with small income, student in art,.... and project with higher goals need to be directed toward middle higher income population.

### What are some limitations of this dataset?

The dataset is recorded in US dollars while the lot of projects were launched in different countries around the globe that use different currency, the analysis is biased because a goal of 750 GBP should be in the range between 1000and 4999.

the other limitation is the dataset contain campaign launched for a small amount of money few dollars which biase the information.

### What are some other possible tables and/or graphs that we could create?

*Outcomes based on category to show which category attracted most funds and Add filter plays in Outcomes by launch date.


