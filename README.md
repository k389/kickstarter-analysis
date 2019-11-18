# kickstarter-analysis
Analysis on kickstarter data

### Challenge

The Questions:	
•	How many Kickstarter campaigns were able to come close to their fundraising goal in a short amount of time, like Louise's play Fever?
•	Does the length of a campaign contribute to its ultimate success or failure?
Kickstarter Data:	
1.	Parent Category = Theater
2.	Subcategory: Plays
The outcomes based on Goal table and graph:	
•	This table summarizes the data of fundraising campaigns, only taking the data from subcategory: plays, that succeeded, failed and were canceled based on their fundraising goal. 
•	Above data shows that most of the the plays' goals that succeeded did not exceed $5000. This shows that a play with a goal of $5000 or less has a about 75% chance of succeeding.
•	The data also illustrates that there are not many plays with fundraising goal of $30000 and more. The plays that had higher fundraising goal were not successful.
•	The data also shows the majority plays fundraising campaigns have a goal up to $20000.
•	The campaigns that have a goal from $10000 to $24000 have a 50% chance of success, which means that there are other factors that will determine the success of the campaign.
Outcomes Based on Launch Date:	
•	The goal outcomes based on launch date shows that the most successful months to launch fundraising campaign (Category Theater) are months of May and June. Out of 166 campaigns 111 succeeded in month of May, and out of 153 campaigns 100 succeeded in June. 
•	This table and graph, however, does not answer if the duration of the campaign determines if a campaign will succeed or fail.
•	The graph also demonstrates that the month of December and January are not good months to start a fundraising campaign. However, the reason why these months are not very successful cannot be answered with this graph and table. 
•	This data is helpful to determine when to run a campaign in order to succeed.
	
Analysis (Questions 1 & 2):	
•	If Louise's play "Fever" fundraising goal was $10000 (based on Module 1 data) then there were 39 plays out of 72 which succeeded, within the fundraising goal category between 10000 and 14999. 
•	If Louise lowered the fundraising goal to less than $10000 then there were 622 campaigns that succeeded, however the outcomes based on goals does not show the duration of the campaigns.
•	The limitations of the "outcomes based on goal" and "outcomes based on launch date" datasets are that they do not give data to show the duration of the campaigns. To answer the question of how many campaigns were successful and if the duration of a campaign contributes to the outcome, we need to know the campaign duration. 
•	The Kickstarter dataset has the data of launch date and the deadline of the campaign. We can calculate the difference of these two dates and determine the duration of each campaign in the Kickstarter dataset. We can use the "DATEDIF" formula to determine the length of days of each campaign. Afterwards, we can create a PivotTable and graph to show the goal outcomes based on the duration of subcategory plays campaign. This table and graph will show the correlation between the length of the campaign and the outcomes.

