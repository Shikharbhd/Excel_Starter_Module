# Kick Starter Challenge Analysis

## Overview of Project
The purpose of this project is to analyse various crowdfunding data in order to help Louise determine the factors, **particulary based on Launch Dates and Goals**, in order to make her crowdfunding campaign a success.

## Analysis and Challenges.
The analysis was carried out by studying how different other campaigns performed in their fundraising campaign with primary focus on their launch dates and their funding goals. **Pivot table** was used to _**Summarise and Pull**_ the relevant data required for the analysis while **Pivot Chart** was used to _**Visualise**_ the data.   

### Challenges

#### Common Challenge: 
a.  In both deliverables, figuring out which fields to put in the report while inserting pivot table seemed to be a bit tricky. This was overcome by multiple trial and error process.  

#### Deliverable 1:
a.	Auto sorting the campaign outcomes in descending order did not work so therefore I googled how to manually move the columns and applied it. I eventually figured out that I need to go into 'More Sort Options' and change the Parameter to _'Count of Outcomes'_.

![AutoSorting](https://user-images.githubusercontent.com/85258893/122688074-1501f600-d1e8-11eb-8d32-628c248a4a1a.png)

b.	Likewise, I was also able to get the months in the row after much trial and error and playing with the fields. 

#### Deliverable 2:
a.	While the values and graph were all correct, I could not manually change the column title from ‘Sum of Percentage Successful’ to ‘Percentage Successful’ as shown in the    solution. _**‘PivotTable field name already exist’**_ message box would appear every time I tried to change it to ‘Percentage’, therefore, I replaced ‘percentage’ with ‘percent’ in the column title.

![Naming_Error](https://user-images.githubusercontent.com/85258893/122686170-e5e68700-d1dd-11eb-9475-f19636d026bb.png)

## Conclusions

### Outcome Based on Launch Dates
a.  More Kickstarter campaign were launched in the months of May and June. Campaign launched in May were most successful.  
b.  Campaign launched during summer tend to be more successful than campaigns launched in winter. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85258893/122686083-6062d700-d1dd-11eb-84be-30b8d89003be.png)

### Outcome Based on Goals
a.  While none of the Kickstarter campaign were cancelled, campaign goals between 20000-35000 and above 40000 were largely unsuccessful suggesting that launching greater number of smaller campaign goals would lead to more successful campaign.  

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85258893/122686100-7ff9ff80-d1dd-11eb-9bdd-072481727f56.png)

## Limitation of Dataset.

The dataset does not identify backers type, whether they are individuals or companies. Backers identity could suggest what goals (higher or lower) to set in relation to similar backers.

## Other possible tables and/or graphs

a. Outcome based on geographic region.

b. Outcome based on length of campaign period. 

c. Relation between number of Backers and Outcome Goals.
