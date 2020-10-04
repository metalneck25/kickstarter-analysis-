# An Analysis of Kickstarter Campaigns
MODULE_1 Performing analysis on kickstarter data to uncover trends

## Overview of Project
Visualizing capaign outcomes from Kickstarter dataset based on their launch dates and their funding goals

### Purpose
Helping Louise see the different campaigns relation to their launch dates and their funding goals compared to her own results

## Analysis and Challenges
An overview of analysis for both sets of visualization of dataset

### Analysis of Outcomes Based on Launch Date
The largest point of analysis to note is the month launched across the succesful campaigns. May, June and July are the peak months within this subset. The failed subset of campaign data is fairly even throughout the year regardless of month launched. ![SS_OBOLD](metalneck25/kickstarter-analysis-SS_OBOLD.png)

### Analysis of Outcomes Based on Goals
Without digging further in to more cross-comparison categories for this subset it is hard to pull anything general of assistance for Louise. The failure rate for every value under $50,000 is higher than the success rate. To be able to explain why the success rate is higher with a goal above $50,000 we would have to look at other factors of the individual play campaigns. 

### Challenges and Difficulties Encountered
Within COUNTIFS: I had to play around with the formula a little bit, but eventually figured out I had to use 'Kickstarter!' for both values I was after.
With my pivot chart for 'Outcomes Based on Goals': I was hung up on appearence and then realized I needed to remove the '(blank)' value from my Row Labels. 

## Results
Theater Outcomes based on Launch Date: The highest number of successful campaigns were launched in the Summer months; The number of failed campaigns was not hinged on which month the campaigns were launched. 
Theater Outcomes based on Goals: The highest number of successful campaigns were those with goals over $50,000, and the success rate of campaigns with goals under $50,000 was much lower across the board than those with goals over $50,000.
I believe combining these two datasets as well as layering length of campaigns, country, and expanding the goal values in to more in-depth information would lend Louise the answers she is looking for. 
