# Election_Analysis_Challenge

## Project Overview
	The general overview of the project was to complete an election audit in Colorado for the Colorado Board of Elections
The project completed an election audit by calculating key indicators in both the candidates who were running and each county turnout

1. Calculating total number of votes cast
2. Key candidate indicators calculated include:
	- Compile a list of candidates who received votes
	- Total number of votes for each candidate
	- Percentage of votes of each candidate (over total number of votes)
	- Determining the winner candidate based on popular vote
3. Key county indicators:
	- The voter turnout for each county
	- The percentage of votes from each county out of the total count
	- County with the highest turnout

## Election-Audit Results
	There were three candidates who received votes in the elections, with one clear winner.
1. The three candidates who received votes:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
2. Total number of votes cast:
	- 369,711
3. Breakdown of votes (and percentage of total votes for each county)
	- The results are as follow:
		1. Diana DeGetter: 73.8% of votes (receiving 272,892 out of the 369,711 votes)
		2. Charles Casper Stockham: 23% of votes (receiving 85,213 out of the 369,711 votes)
		3. Raymon Anthony Doane: 3.1% of votes (receiving 11,606 out of the 369,711 votes)
	- Total votes in each county (ranked highest to lowest):
		1. Denver: 82.8% of votes (306,055 votes were cast in Denver alone out of 369,711 votes)
		2. Jefferson: 10.5% of votes (38,855 votes were cast in Jefferson out of 369,711 votes)
		3. Arapahoe: 6.7% of votes (24,801 votes were cast in Arapahoe)


1. County with the largest number of votes:
	- Denver county had the largest number of votes with 306,055 votes cast.
2. Candidate who won the election (along with vote count and percentage):
	- Diana DeGetter won the popular vote with 272,892 votes cast in their name. Diana DeGetter received 73.8% of the votes.

## Election-Audit Summary
	While the code used in the script and audit were for the Colorado Board of Elections, the code may be used in other elections as well.
Throughout the code, there was no explicit mention of locations (such as Colorado, Denver, etc...) or names of candidates running in the election.
Some of the basic script used: 
```
candidate_options = []
candidate_votes = {}

county-options = []
```

Hence, the general format of the script can be used, albeit with some modifications, for any election. Some modifications may include:
1. Depending on the data file used, the script might have to change 