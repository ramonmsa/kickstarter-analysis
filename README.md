# Kickstarting with Excel
## Overview of Project
This project uses the Kickstarter dataset to visualize campaign outcomes, which falls in the "*play*" subcatergory, based on their launch dates and their funding goals. 

### Purpose
To provide an overview on how different campaigns performed in relation to their launching dates and their funding goals. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
Based on the chart "*Theater Outcomes Based on Lauch Date*", May, June and July were the months with higher quantity of successful campaigns with numbers above 80. However, May was the one with the highest number with a total of 111 cases. 

On the other hand, December was the month where campaigns least succeed with one third of the amount presented in May.


![Theater_Outcomes_vs_Launch](https://raw.githubusercontent.com/ramonmsa/kickstarter-analysis/main/resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
Campaigns with less than $1,000 goal are the most outstanding with almost 80% of the cases, followed by campaigns with targets between $35,000 and $44,999 having 67% of successful cases, as it is shown in the chart "*Outcomes Based on Goals*". 

Nevertheless, 100% of the campaigns aiming from $45,000 to $49,999 failed.

![Outcomes_vs_Goals](https://raw.githubusercontent.com/ramonmsa/kickstarter-analysis/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
One of the challanges encountered is the small amount of data from the years 2009 to 2013. In order to work it around, it was necessary to look the data by month throughout all the years found in the database, since it was understood that these years with low volume of data influence on the result is minimal.

Another difficulty was finding campaigns's goal extremely low in the datase. Goals as low as $1.00 could jeopardize the results of analysis. Luckly, none of these inconsistent goals were within the set of data when it is filtered by parent category "*Theater*" which is the category needed for this analysis. 
## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**
    - The most promising month to launch a campaign is May.
    - The least promissing one is December.
- **What can you conclude about the Outcomes based on Goals?**
    - Campaigns which goal is less then $1,000 have more chance to succeed.
    - Campaigns which goal is over $45,000 has almost no change to succeed. 
- **What are some limitations of this dataset?**
    - The high number of outliers  
    - Data only up to 2017 which makes it impossible to analyse the interference of the current global pandemic on the outcomes.
- **What are some other possible tables and/or graphs that we could create?**   
    - We could create chart to show an average of backers per play based on Goals filtering by the successful campaigns.
    - Another chart presenting the average duration period of successful campaigns in relation to the Goal, could be also helpful.
