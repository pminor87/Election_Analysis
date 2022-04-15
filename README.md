# Election_Analysis

## Overview of Election Audit
This is an analysis of a congressional election held in Colorado and conducted for the Colorado Board of Elections.
The purpose of the analysis is to find:
- The total number of votes cast.
- Amount of votes per county.
- County with the largest turnout.
- Amount of votes won by each candidate.
- The winner of the popular vote.

## Election-Audit Results
- How many votes were cast in this congressional election?
	- 367,711
	
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
	- Jefferson: 10.5% (38,855)
	- Denver: 82.8% (306,055)
	- Arapahoe: 6.7% (24,801)
	  
- Which county had the largest number of votes?
	- Denver
	
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
	- Charles Casper Stockham: 23.0% (85,213)
	- Diana DeGette: 73.8% (272,892)
	- Raymon Anthony Doane: 3.1% (11,606)
	
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
	- Winner: Diana DeGette
	- Winning Vote Count: 272,892
	- Winning Percentage: 73.8%
	
										![Election Results Analysis](https://github.com/pminor87/Election_Analysis/blob/main/Resources/Images/Election%20Results%20Analysis.PNG)

## Election-Audit Summary
The python script used to execute the election results for the State of Colorado can also be used for other elections with some small modifications:
	- "file_to_load and file_to_save = os.path.join("", "")" would need to be modified based off the file name and location.
	- If the csv file is formatted differently then we would need to modify candidate_name = row[2] to look for the candidate name from row 3 to the proper row. The same would go for county = row[1].


