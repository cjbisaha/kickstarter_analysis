# Kickstarting with Excel

## Overview of Project

	### Purpose
		The purpose of the this assignment was to dive into different campaigns using the Kickstarter 
		dataset to look at the realtionships of success with respective launch dates and funding goals.
		Lousie's play "Fever" had closed in close to its fundraising goal in a short amount of time, Ie 
		wanted to dig deeper to see if she if she could have possibly seen different results when breaking
		down factors of her fundraiser. 


## Analysis and Challenges

	### Analysis of Outcomes Based on Launch Date
		When looking at launch dates, I built a pivot table to break our data up with the needed filters. I 
		got all the theature 'Parent Category" data and broke it up between each month. I then broke my data up 
		into successful, failed and canceled columns. This will allow me to look to see what months had the most
		success based off their launch date month. The challanges you could face is making sure you have all the correct
		filters to ensure you were not looking at any unneeded date. Once i had all my relevant data I created a
		line graph to visually represent the theature outcomes with their respective launch month. 




	### Analysis of Outcomes Based on Goals
		Next I created a table to compare what the success rate was compared to the original goal value. I broke the data up 
		by the goal amount and the outcomes by breaking the goal into incruments of 5000s. To do so, i used a =countifs()
		formula that would count the amount of  'successful', 'failed', and 'canceled' outcomes broken into goal intervals.
		The challanges i faced during this componet was getting the correct data from the correct data sheets into the formula. 
		Once I determined the correct formula, I was able to apply it to all cells, but still had to go into and edit each formula
		to give me the correct result for each cell. Once the correct count for each category was determined, I divided it by the
		Total Projects for each goal price range. Doing so I was able to determine the percantage of 'successful', 'failed', and 
		'canceled' outcomes for each respective goal range. Using this data I created a line graph to show which fundraisers
		goal target worked best, or worst. 


			=COUNTIFS(Kickstarter!$D:$D, "<1000",Kickstarter!$F:$F, "successful", Kickstarter!$R:$R, "plays")


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	From my analysis, I can determine that the most succesful outcomes are during the months of May and June. The most failed outcomes
	was also in May, but it had the highset differential between succesful and failed outcomes. This is due to May having the largest 
	amount of launch dates. I still beleive from this graph that launching in May will give you the highest chance of success.
