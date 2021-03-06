# Election_Analysis
## Project Overview
Analyzing election results for a Congressional District in Colorado using Python. The following tasks were asked to be completed in this assignment

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate won
4. Calculate the percetage of votes each candidate won
5. Determine the winer of the election based on popular vote. 

## Resources
Data source: election_results.csv
Software: Python 3.7.6, Visual Studio Code 1.38.1

## Summary 
The analysis of the election show that:
* There were 369711 votes cast in the election.
* The candidates were:
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony Doane
* The candidate results were:
  * Charles Casper Stockham recieved 23% of the vote and 85213 number of votes.
  * Diana DeGette recieved 73.8% of the votes and 272892 number of votes.
  * Raymon Anthony Doane recieved 3.1% of the votes and 11606 number of votes.
* The Winner of the election was:
  * Diana DeGette who received 73.8% of the votes and 272892 number of votes.
  
# Election_Analysis Challenge 
## Project Overview
Expand analysis of the election results for a Congressional District in Colorado using Python. The following tasks were asked to be completed in this assignment in addition to previously determined data:

1. Number of votes for each county
2. Percentage of votes from each county out of the total count
3. County with the highest turnout

In addition to:
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate won
4. Calculate the percetage of votes each candidate won
5. Determine the winer of the election based on popular vote.  

## Resources
Data source: election_results.csv
Code source: PyPoll_Challenge_Starter_Code.py
Software: Python 3.7.6, Visual Studio Code 1.38.1

## Results
Total Votes in Congressional Election:
* 369,711

County Breakdown of Votes:
* Arapahoe: 6.7% (24,801)
* Denver: 82.8% (306,055)
* Jefferson: 10.5% (38,855)

Largest County Turnout:
* Denver

Candidate Breakdown of Votes:
* Charles Casper Stockham: 23.0% (85,213)
* Diana DeGette: 73.8% (272,892)
* Raymon Anthony Doane: 3.1% (11,606)

Winner of the Election:
* Winning Candidate: Diana DeGette
* Winning Vote Count: 272,892
* Winning Percentage: 73.8%

![Deliverable_1_Terminal_Data](https://user-images.githubusercontent.com/88064181/129998217-ce4b85eb-243e-4c66-8285-14c57b5a4d90.png)
![Deliverable_2_Election_Results_text](https://user-images.githubusercontent.com/88064181/129998221-5542ca57-a1c3-4019-bd5e-f98614b8b396.png)


## Election Summary
### Purpose of Election Audit
This election audit did more than verify the results of the recent election. It gave officials and candidates a breakdown of where votes were coming from, and how those votes are divided percentage-wise. By breaking down where the votes were coming from, election officials and candidates can draw lots of useful information. Without knowing the population of the different counties, we do not know how much of each county's population actually voted, but base on the voter turnout shown here, election officials may try to encourage voting in Arapahoe and Jefferson since they had a much lower voter turnout compared to Denver. Again, Denver county may have that many more people than the other two counties, but it is data that would be useful to know. Furthermore, future candidates can use this audit to see where they should be focusing their campaigns. Based on this data, potential candidates should be focusing 80% of their time in Denver to hit the most potential voters. 

### Re-purposing Election Audit Script
This Election Audit script is useful for more than just auditing this congressional election. With proper changes, the election commission can be used for any election. One can expand the datapool by adding lists for multiple congressional districts that have dictionaries of the counties in each district. Each district can then be isolated for individual results, or, in terms of a statewide election, such as the presidential election, every county and every district can be run for voting results. To expand upon this further, once the list of districts is made, each districted can be assigned a value representing how many electoral college votes each district has. When run through the modified script, the value of the number of votes, the percentage of votes, and the number of electoral college votes assigned could be displayed for each candidate. '

If the election commission doesn't want to get that into depth, but would like clear, defined winners, the majority vote number could be changed. Right now this script is running to determine popular vote at 50%+.1%. This is not a comfortable margin of victory. In most cases, a candidate winning by 50.1% of the vote would call for a recount. If the election commission would like this information processed immediately, the script can be updated to declare no winner when candidates in the majority are between 50.0001% and 53%. Since 54% is a comfortable margin of victory for the majority, the script can be coded to declare a winner at 54%+. 
