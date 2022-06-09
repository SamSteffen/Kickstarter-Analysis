# An Analysis of Kickstarter Campaigns
The following is an analysis of Kickstarter data to discover trends to help our client, Louise, determine strategies for launching a fundraising campaign to fund her play, "Fever." She's estimating needing a budget of $10,000 and is feeling hesitant about starting her first campaign.

# The Data
To determine the best course of action, a dataset was analyzed containing 4113 project campaigns across 9 different performance/media categories, throughout 21 countries between the years of 2009-2017. Based on this data, the findings were as follows:

# The Findings
- Filtering for only the United States campaigns, 525 were successful theater Kickstarters.
- While there are only a total of 604 Kickstarter campaigns for plays in Great Britain, the "theater" category is the most successful. 

# Outcomes Based on Launch Month
![Outcomes Based on Launch Month](https://user-images.githubusercontent.com/104729703/172745605-d7d4b211-d73e-44c2-a188-8acfa1264725.png)
---
- The above chart demonstrates outcomes based on the month of the campaign's launch. We can see by looking at our new chart that the months of May and June both have a greater success rate. The month that launched the most successful Kickstarter campaigns was May. However, January, June, July and October all had roughly the same number of failed campaigns launched.

# Outcomes Based on Parent Category in the US
![US Parent Category Outcomes](https://user-images.githubusercontent.com/104729703/172745672-e0389bd4-1559-4b37-a0e7-b2a7e6ef1b0d.png)
---
The above chart demonstrates the outcomes of Theater Campaigns in the US. Just by glancing at the data, we can determine that theater is a popular and successful type of campaign overall. By using filters, we can see that theater follows the overall trend: there is a spike of successful campaigns that began in June, but that tapers off by the end of the year. By comparison, the data around technology campaigns reveals a different story. Instead of one large spike, their trend lines are a bit all over the place and less predictable.

# Comparison Case Study 1: "Foresight"
- We examined a play from Great Britain that Louise enjoyed, "Foresight", a campaign that was successful. The average donation for this play was surprisingly high, considering it had only 17 backers. The campaign also wasn't active for very long—just under a month.

# Comparison Case Study 2: Edinburgh Festival
- We also looked closely at 5 plays from the Edinburgh Festival Fringe, each of which presented a successful fundraising campaign in a range from $1k to $4k, and succeeded with an average donation of $41 per backer.

# Descriptive Statistics:
- The attached spreadsheet contains a sheet called 
-   comparing the two, we'll be able to determine whether there are any trends between the goals and pledges in successful or failed campaigns.
-   This simple table allows us to determine a few things. For one, failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns. Louise is asking for more than twice the average successful Kickstarter goal, so this isn't great news for her campaign. In addition, the mean and median pledged amounts are much lower than the successful pledges, which indicates that failed Kickstarter campaigns are unsuccessful for reasons other than asking for too much money. In other words, if the failed projects were also getting a median pledge amount of around $3,000, it's possible that those that failed just asked for too high of a price. Since the median is much lower, there must be another factor keeping people from pledging to those unsuccessful projects. 
- The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.
- The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.
- Some large values are driving all of these distributions. The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. This would indicate there must be some failed Kickstarters with really high goals!

# Outliers
![GB Musicals Goals and Pledges](https://user-images.githubusercontent.com/104729703/172758128-9700195b-6b0c-4209-a58c-76a4a0d2ebfa.png)
- From the above plots, which represent the goals and pledges for musicals in GB, we can see that the mean campaign goal is around £4,000. This is outside of the range of outliers for amount pledged.

# Some recommendations for starting your own Kickstarter would be:
* Launch your kickstarter in the month of May if possible; avoid launching in December.
* You might want to launch your play in GB, as plays were listed as the most successful type of campaign launched, category-wise.
* You should probably try to get your play produced for less than £4,000, judging by the fact that half of the campaign goals for musicals in GB were less than £2,000, which is just over the 3rd quartile for amounts pledged.
