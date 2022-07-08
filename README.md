# Kickstarting with Excel
## Overview of Project  
### Purpose
The purpose of this project is to help Louise with her first crowdfunding campaign to fund her play fever, determinating which ones are the specific factors to determinate a project´s campaign successful and helping her to gain a better understanding of campaigns in her category (theater) to make her campaign´s play successful. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To obtain the analysis of outcomes based on launch date, first, I converted the unreadable dates into normal dates, helping me with the formula called: DATE, so that any user could read them. Then, I added a column called years to have only the year when the crowdfunig campaign started, to do this I used the formula called: YEAR.

![image](https://user-images.githubusercontent.com/108365182/177886669-7e2d4fbf-ff42-4e4e-97f1-3eb6b6ef18e2.png)

Then, I created a pivot table based on the database. I putted in the rows the launch date, then, I separated them in months to have a deeper analysis. After that, on columns and values I inserted the outcomes and finally in the filters I putted the parent category and the years.

![image](https://user-images.githubusercontent.com/108365182/177887243-8a732748-3ab3-4694-892b-7132a29e3655.png)

Finally, based on the pivot table, I created a line chart to visualize and analyze better the information.

![image](https://user-images.githubusercontent.com/108365182/177887353-3e45682f-6dc9-45ba-bcf6-f646da95f6a8.png)


### Analysis of Outcomes Based on Goals
To obtain the analysis of outcomes based on goals, first in the original kickstarter sheet, I filtered the parent category in theater and then, I separte with colors all the campaigns that were successful, canceled and failed; this, to have a better general visualization on the number of each outcome, doing this with the help of conditional formatting. 

![image](https://user-images.githubusercontent.com/108365182/177826865-97e522a8-d35a-42a3-b2d8-76850464f8a3.png)

Then, helping me with the formula in Excel called: Countifs. I determinate the specific number of successful, failed and canceled campaigns in the parent category of theather. Based in the kickstarter dataset, I used the criteria of outcomes (successful, failed and canceled), goals (fund goal in each campaign) and the subcategory (plays), to do it more specifically. Next, after I had the number of each outcome in the different funds goal, I sum all the campaigns to have the total projects in each goal, using the formula sum in Excel.

![image](https://user-images.githubusercontent.com/108365182/177829043-aca88672-5d7e-4c00-805e-dbff2a750876.png)

After that, to obtain the percentage of each outcome, I used the formula called: ROUND with 0 decimals, and inside it, I divided the number of projects in each outcome with the number of total projects in the corresponding goal, this, multiplying it for 100, to obtain the percentage.

![image](https://user-images.githubusercontent.com/108365182/177832758-f072c38c-2b84-4534-950c-7e4bca723f2b.png)

Finally, to facilitate the anlysis to Louise, I inserted a line chart with the new data, to easier visualize the percentage of each outcome and goal.

![image](https://user-images.githubusercontent.com/108365182/177834586-e85d454a-71e0-47bf-bbef-17a127d3f001.png)

### Challenges and Difficulties Encountered
One of the biggest challenges encountered for me was the unreadable dates, I did not know how to convert them in normal dates, so what I did was learn through a video different options of how could I do it. Specifically, what I did was use the formula DATE, which convert them easier than the other option that was converted them in an external page. 

The other challenge that I had was create the pivot table of outcomes based on Launch Date without help, this is because I wanted to analyze the infomation to organize it in the pivot table. What I did was look the first database to see how did I organize the information to create a table, then I applied my knowledge to the new one. This challenge was more difficult than the first one.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the line chart, we can deduce that the second trimester of the year is the best to start a crowdfunding campaign, this is because more than 80% campaigns were successful, otherwise, the last trimester of the year is the worst to start a campaign because at least 30% failed.

In the other part, we can deduce that october is a risky month, because you have almost the same number of campaigns that failed and had succesful. So, if Louise is a risk lover, I recommend her to start her crowdfunding campaign in october, but if she is a risk averse, I recommend her to start her crowdfunding campaign in may.
- What can you conclude about the Outcomes based on Goals?

According to the line chart obtained by the data analysis, I conclude that the best for Louise is to reduce half of her fund goal, she initially planned a fund goal of 10,000 dollars. So, I recommend her to have a fund goal less than 4999 dollars, and if she decide to have a fund less than 1,000 dollars is even better to her campaign.
- What are some limitations of this dataset?

One of the principal limitations in this dataset is that it does not show more information about the backers, who are essential in the crowdfunding campaigns. First, it does not tell us if the play was a successful or a failure for the public, this, because affect directly in the backers for the next crowdfunding campaigns. Then, the dataset does not tell us the capacity of each backer who funded the play, which is essential to know, because in some cases you will only need one, while in other cases you will need more than 60 backers.
- What are some other possible tables and/or graphs that we could create?

To have a deeper analysis we can analyze the outcomes based on the backers count and the outcomes based on average donation.
