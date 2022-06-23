# Kickstarter Analysis 

## Overview of Project
This project was created to compare different crowdfunding campaigns to better inform a person who wants to start their own crowdfunding campaign for a play. To do this, we looked at different crowdfunding projects for various categories ranging from film to music to theater, among others. We also used other important data, such as pledged money, country the crowdfunding took place, and the outcome of each campaign, to know how successful each crowdfunding campaign was and use that information to better understand what conditions are needed in order for a crowdfunding campaign to be more likely to be successful. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Dates

In order to have a better understanding of when is the best time of year to launch a crowdfunding campaign, we looked at the number of successful, failed, and canceled campaigns and the month they were created. With this information, we can have a better idea of when crowdfunding campaigns are more likely to be successful and when they are more likely to fail. Below is the graph we got when looking at the success rates for theater campaigns 

![Alt text](https://github.com/dntalx/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

As we can see, May, June, and July are the best months to create a campaign to increase the chances of it being successful, with May being the best month of the year. On the other hand, December and October are the worst months of the year to start a campaign as the success-to-fail ratio is really low, with December being the worst having almost 50% of their campaigns failing.

### Analysis of Outcomes Based on Goals

We wanted to look at the percentage of successful and failed crowdfunding campaigns based on the monetary goal of each campaign to see what goals were more likely to succeed and which ones were more likely to fail. We created 12 ranges starting with campaigns whose goals were less than $1,000 and from there, we incremented each range by $5,000 going all the way up to $50,000 or more as the campaign’s goals. In the graph below, we can see the success and failed range based on the amount of money a campaign set as its goal.

![Alt text](https://github.com/dntalx/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

The most successful campaigns were those whose goals ranged from “Less than $1,000” and “$1000 to $4,999” being 76% and 73% respectively. It is also significant to point out that campaigns that ranged from “$35,000 to $39,999” and “$40,000 to $44,999” were also very successful both having a success rate of 63%. However, both ranges had only 6 and 3 campaigns each respectively. Campaigns whose goals were from “$25,000 to $29,999” and “$50,000 or more” were the least having a 20% and 13% success rate respectively. It is important to mention that there was only one campaign whose goal ranged from  “$45,000 to $49,999” that failed, meaning that in the graph, it has a success rate 0%. This will be discussed in the next section when we go over some of the challenges we encountered with the data given to us.

### Challenges and Difficulties Encountered

After analyzing the data that was provided and running some of the analyses to figure out the best circumstances in order to have the best chance at a crowdfunding camping to be successful, we encountered some problems while doing the “Outcomes Based on Goals” analysis as some ranges had very few crowdfunding campaigns to give us a better understanding for what is the best range in order to increase the likeliness a campaign will be successful. 

When looking at the range “$45,000 to $49,999,” there was only one campaign with that range, giving us a 100% chance of failing or succeeding. In this case, the only campaign with this range failed, giving us a 100% fail rate. There were other ranges with few campaigns in them that, while they didn’t give such an extreme result, it isn’t enough data to confidently say that those ranges for the goal of crowdfunding campaigns increase or decrease the likelihood they will be successful.

## Results

When considering the best time of the year to start a crowdfunding campaign, February to July is the best overall time, with May having the best success rate out of any other month. On the other hand, the worst months to start a crowdfunding campaign are October and December, with December being the worst month to start a crowdfunding campaign.

Taking the information we got from the “Outcomes Based on Goals” graph, we see that the best ranges to set a crowdfunding campaign are “Less than $1,000” and “$1000 to $4,999.” 
On the contrary, the least successful ranges were “$25,000 to $29,999” and “$50,000 or more.” 

Like mentioned on the Challenge section, we need more information about other crowdfundding campaigns that have different goal ranges to best determine what goals are more likely to be successful. 

Another piece of information we could look at is the timeline from when the crowdfunding campaigns were created and when they ended and see if that has any significant information to determine how long a campaign should run to get the best results.  
