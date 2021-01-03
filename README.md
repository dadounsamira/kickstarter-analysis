# Kickstarting with Excel

## Overview of project
The purpose of this analysis is to provide Louise with readable documentation to gain insight on how different campaigns fared in relation to their launch dates and their funding goals. 


### Purpose
Louise **Fever** reached the goal on a short amount of time, Louise wants to understand the elemets that play a significant role on determing the success or failure of a compaign. This analysis will shed light on how some factors contribute to success or failure to a compaign such as when to launch a compaign,the bakers preferences and countries that get the most funds. Using this kickstarter dataset will help deliver outcomes in respect of Louise needs.
Included the source of this dataset ![here](/Kickstarter_Challenge .xlsx.zip)




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

[here]

### Analysis of Outcomes Based on Goals
![here](/resources/Outcomes_vs_Goals.png)
For this analysis we used the function COUNTIFS to visualize  the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis, applying the following fields:
* Goal, Number Successful,Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed and Percentage Canceled in columns 
* Amount ranging between less than 1000 and greater than 500000 in rows so  so projects can be grouped based on their goal amount

The formula for the Countifs is : =COUNTIFS(kickstarter_challenge!D:D, "<=1000", kickstarter_challenge!F:F,"successful",kickstarter_challenge!R:R,"plays")

