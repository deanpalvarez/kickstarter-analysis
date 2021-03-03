# Kickstarting with Excel

## Overview of Project

The purpose of this analysis is to determine the relationship between the launch dates and funding goals of various Kickstarter campaigns, specifically in the theater/plays category. We determined which ones were successful, canceled, or failed. We want to know the reason for these outcomes, so we did this by comparing/analyzing the launch dates, as well as the fundraising goals. Both launch dates and funding goals vary greatly from one campaign to the next, so a number of steps must be taken in order to extract the most accurate information possible, while considering limitations.

### Analysis of Outcomes Based on Launch Date

We have a rather large spike in successful campaigns for the month of May (from all the years in the dataset). When we filter out the specific years of 2014, 2015, and 2016, we notice a similar trend, but the spike(s) of the successful campaigns are somewhat matched by the failed ones. Considering all the data together, we see that most campaigns are launched in roughly this spring/summer period, and of those, are most of the successful ones. Because this is generalized to Theater and not specifically Plays, this is information worth noting when considered in conjunction with the latter, but is not exactly enough to help Louise on its own.

### Analysis of Outcomes Based on Goals

Here we notice an almost direct correlation between successful/failed campaigns in the same goal range. It appears as if they are inversely related to one another, and alternate as the goal tiers increase. What we see is that campaigns with a goal under $1000 seem to be very successful, whereas the exact opposite becomes true in the $25-30K goal range, and is once again inflated even more for campaigns with goals above $45K. This is contradicted when we see the success of campaigns in the $35-40K range. This is to a lesser extent, but it’s enough to fairly say we can’t just conclude outright that most campaigns fail when their goal is too high. A fair conclusion to make from this dataset is that these Kickstarter campaigns tend to succeed at a higher rate when the initial goal is set much lower, and it doesn’t appear to be much of a deterrent for people, whereas setting too high of goal is. However, this should remain a fairly generalized conclusion, as there are still several factors to consider that are beyond our limitations.

### Summary and Conclusion

We could over generalize from all this data and say that setting a lower Kickstarter goal and launching it in the month of May would lead to a successful campaign. However some subjective limitations to consider are things like a prior following/fanbase, strategy of advertising, etc. Within our database, we could further analyze the relation of amount pledged to original goal, average donations, length of campaign, etc. and all these datasets can be interchanged, filtered through pivot tables/charts, and separated by success/failure/cancellation.

