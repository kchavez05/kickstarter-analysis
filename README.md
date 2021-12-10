# Kickstarting with Excel

## Overview of Project
This analysis examines the outcomes of Kickstarter campaigns started between 5/17/2009 and 3/15/2017 for projects listed as "Plays". 

### Purpose
We explore the results from two perspectives.  First, we look at Outcomes Based on Launch date to determine if there are advantages to starting a campaign during a certain month of the year.  Secondly, we explore Outcomes Based On Goals to assess the relationship between a campaign's Goal amount and its likeihood of success. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Our data show us that campaigns begun in May were significantly more successful than those launched in other months.  The first quarter of the year was up and down before spiking in May.  Successes then trended downwards through the summer, increased slightly in October, and bottomed out in December.  
![image](https://github.com/kchavez05/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Our data indicate that outcomes for these campaigns based on the fundraising goal were successful to a point, went through a bit of a deadzone, and then became successful again.  The greatest rate of success (76%) was for those campaigns whose goals were less than $1000.  Successful campaigns continue to outweight failed campaigns until they intersect at a range of $15,000-$19,999.  At this point failures are more frequent than successes, with peak failure (80%) at a range of $25,000-$29,999.  However, at the ranges of $35,000-$39,999 and $45,000 to $44,999, campaign successes again became more common (67% successes vs 33% failures).  Very few campaigns with goals above $45,000 were successful.
![image](https://github.com/kchavez05/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
None.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1) It appears that May is the best month in which to launch a Kickstarter campaign for plays.
2) It would be unwise to launch a campaign in December.

- What can you conclude about the Outcomes based on Goals? 

The sweet spot for successful campaigns has a cap of about $5000.  At the ranges of Less than $1,000 and $1,000-$4,999 the rates of success are 76% and 73%, respectively.  Beyond $4,999 the rates drop quite close to 50/50 and plummet over a range of $15,000-$19,999.  There is a range of success between $35,000 and $44,999, but the sample size for those campaigns is only 9, so they represent just 0.86% of total campaigns and could be considered outliers.  

- What are some limitations of this dataset?

Over 65% of the data recorded are from campaigns in the United States (912 of 1393), so these results may not be representative of campaign success in other countries.  Campaigns in Great Britain, for example, only represent about 26% of the data, though the Outcomes Based on Launch Date are nearly identical.  Further analysis is recommended for any projects outside the United States.  Additionally, the data are old and may not be relevant, especially considering recent global economic conditions and social restrictions due to the Covid-19 pandemic.

- What are some other possible tables and/or graphs that we could create?


These data could absolutely be broken out by Country, as cultural priority for the arts as well as GDP per capita would likely have a significant impact.  Additionally, one could further analyze the campaigns by genre of play - for instance, are comedies more often supported than tradgedies?  Again, if we had access to more data we could look at pledges per impression to measure the impact of the campaign's design and answer - of the people who see the campaign, how many donate and how much do they give?  This could be informative for campaign aesthetics and marketing purposes.
