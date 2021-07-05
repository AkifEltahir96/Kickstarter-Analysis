# Kickstarting with Excel

## Overview of Project


### Purpose

The purpose of this analysis is to determine the degree of success Kickstarter campaigns have in relation to their launch dates and funding goals. Louise wants to complete this analysis to evaluate how her campaign compares to other campaigns worldwide.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

First, I created a pivot table to analyze the success of Kickstarter campaigns based on launch date [picture]. Through the pivot table, I filtered data by month of Kickstarter campaign launch (Years) and type of Kickstarter campaign (Parent Category) [picture]. Next, I only included campaigns that were successful, failed, or canceled [picture]. I did not include live campaigns because those are currently ongoing. Since Fever is a theater Kickstarter campaign, I filtered the data through type of Kickstarter campagin to only show theater campaigns [picture]. This will allow for a more relevant comparison. Finally, I created a line chart to  visualize the relationship between launch month and Kickstarter campaign outcomes. The chart can be viewed here (C:\Users\Owner\Desktop\Excel Module\Crowdfunding Analysis\Resources\Theater_Outcomes_vs_Launch.png).

### Analysis of Outcomes Based on Goals

First, using the COUNTIFS formula, I determined the number and percentage of Kickstarter campaigns that were successful, failed, and canceled depending on their fundraising goals[picture with example formula].  Next, I created a line chart to visualize this relationship. The graph depicts the percentage rate of success, failure, and cancellation (Y-axis) with regards to Kickstarter campaign fundraising goals (X-axis). The chart can be viewed here (C:\Users\Owner\Desktop\Excel Module\Crowdfunding Analysis\Resources\Outcomes_vs_Goals.png).

### Challenges and Difficulties Encountered

I did not encounter any challenges and difficulties with the analysis. The instructions were very clearly laid out and completing the module was a stress-free experience. However, any possible challenges or difficulties that someone could encounter include confusion as to why the canceled Kickstarter campaigns did not have any indication of what the intial fundraising goals were. Also, there is no understanding as to why those Kickstarter campaigns were canceled.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

One conclusion you can draw about the Outcomes based on Launch Date (Theater_Outcomes_vs_Launch.png) line graph is that in each month, most Theatre Kickstarter campaigns are successful. Some campaigns do fail while very few, or none, are canceled. Another conclusion is that the number successful Theater Kickstarter campaigns peaks in May and begins to steadily decline in the months afterwards.

- What can you conclude about the Outcomes based on Goals?

One conclusion observed on the Outcomes Based on Goals line graph (Outcomes_vs_Goals.png) is that Kickstarter campaigns with lower fundraising goals tend to be more successful than Kickstarter campaigns with higher fundraising goals. As you can see in the graph, there is a higher percentage of successful campaigns than those that failed or were canceled when fundraising goals are less than $14,999. When fundraising goals are between $15,000 and $19,999; Kickstarter campaign success and failure percentages are 50%. When fundraising goals are higher than $19,999; success trends are highly inconsistent. Campaigns with goals from $20,000 to $34,999 and $45,000 to $49,999 are more likely to fail. However, Campaigns with goals from $35,000 to $44,999 and greater than $50,000 are more likely to succeed.

- What are some limitations of this dataset?

  One limitation of this dataset is the existence of outliers. Kickstarter campaigns that have higher fundraising goals are very few and are more likely to fail. These fundraising goals may be unrealistic and this can skew the value of statistics such as the average fundraising goal for successful campaigns. 
  Another limitation is that this dataset does not include variables accounting for the socioeconomic status (SES) of the citizens in countries in which the Kickstarter campaigns are based. Citizens in countries with lower SES may not have the funds to donate to these campaigns. This can lead to skewed success and failure rates leading to biased interpretations of the data.

- What are some other possible tables and/or graphs that we could create?

  A few other possible tables and/or graphs that we could create involve comparisons of different countries to see how theatre Kickstarter campaigns fare internationally. Also, we can look at the rate of success, failure and cancelation depending on factors such as value of average donations and number of supporters. 
