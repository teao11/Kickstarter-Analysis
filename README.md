# Kickstarting with Excel

## Overview of Project

This project was based entirely in Excel, and was a great way of building expertise in fundamental Excel skills, including lookups, complext formluae (countifs) and  Pivot Tables.

This project revolved around investigating Kickstarter Data and identifying any trends based on the various outcomes and categories of the campaigns.

### Purpose

The purpose of this analysis is to support Louise as she is trying to understand trends in various Kickstarter Campaigns, so that she may better prepare her own campaign for success.

Specifically in this challenge, Louise wanted to understand how different campaigns fared in relation to:
1. The campaign launch date 
2. Campaign goals

In order to support Louise, I have combed through some Kickstarter Campaign data and created visualizations to help explain my findings to Louise. Please find them included below.

## Analysis and Challenges

The analysis was performed in Excel and utilized the Kickstarter Campaign data provided at the beginning of this module. I have included my Excel spreadsheet in this repository for reference:

[Kickstarter_Challenge_Module.xlsx](https://github.com/teao11/Module-One-Deliverables/files/6412868/Kickstarter_Challenge_Module.xlsx)

I have included the graphs below in their respective sections.

* Please note that I had removed the work for Module One from this sheet, so that it contains work only used for this challenge. I can share the repository with all of module one's work!

### Analysis of Outcomes Based on Launch Date

Using the Kickstarter Campaign data, I have created the following graph for Louise to display the relationship between Campaign Launch Date and the Outcome:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/46773181/116841904-7665fb00-ab8f-11eb-95b6-9aab5248d603.png)

### Analysis of Outcomes Based on Goals

Using the Kickstarter Campaign data, I have created the following graph for Louise to display the relationship between Campaign Goal and the Outcome:

![Outcomes_Based_on_Goal](https://user-images.githubusercontent.com/46773181/116842211-a792fb00-ab90-11eb-9cc0-02e1a39e3ff6.png)

### Challenges and Difficulties Encountered

Personally, I did not experience any challenges while constructing the visuals. All of the skills needed here, I have experience in at work. However there may be a few challenges to those who are less familiar with Pivot Tables and countif statements. Some of these may include:
* Including the correct rows / columns in the Pivot Table
* Ensuring that the Pivot Table contains the correct filters
* Ensuring that CountIf statements contain absolute references when trying to drag formula to other columns
* Ensuring that ALL of the CountIF statements contain the correct filters!

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Some different conclusions we can draw from this analysis include:
1. May, June and July certainly have the most successful campaigns, with 298 successful campaigns (this represents 35% of all successful campaigns). This suggests that Louise may see more success with her own Kickstarter Campaign by launching it in May, June or July.
2. November and December were the months with the least amount of successful campaigns. This suggests that Lousise should NOT launch her kickstarter campaign at the end of the year.

- What can you conclude about the Outcomes based on Goals?

When looking at this graph, it is clear that there is a relationship between the goal and successful outcome of a campaign -- as the goal of a campaign increases, it's likelihood to succeed generally decreases. 
* Please note that we do see the $35,000 to $39,999 and $40,000 to $44,999 buckets defy this statement, but overall it is clear that the larger the goal, the fewer campaigns that succeed.

- What are some limitations of this dataset?

This dataset represents a small portion of the entire Kickstarter Campaign landscape, and so it is difficult to understand whether the sample gives us an accurate picture of the broader dataset.

On top of that, the sample contains A LOT of different campaigns from a wide range of countries. In order to understadn whether these trends apply to all different countries or not, it would be great to have more data from each

- What are some other possible tables and/or graphs that we could create?

It would be interesting to create these same graphs, but slice by country. This would allow us to see if the trends we saw held across the globe, or there were differences based on where the campaign was started.
* This would be relevant for Louise, as she really would only be interested in the trends of campaign where she is launching from. If she is including other countries in her analysis, she may be getting an inaccurate representation of campaign performance in her own country.

Running a deeper dive on the average donation and backer count would certainly be interesting for Louise. This would allow her to roughly understand the count of backers needed for similar campaigns to achieve their goals. She could then use this as a proxy for her own campaign.

We could also take a look at the data by campaign length. Having a longer campaign would mean there is more time to achieve a campaigns goal. Having a longer campaign may / may not make sense to Louise, but it would help her be more strategic when setting her campaign goal.
