# "election-analysis" Week 3 Challenge
### Tools Used
* Microsoft Excel
* Python Scripting
## Overview of the Project / Election Audit
<!-- Explain the purpose of this election audit analysis. -->
The purpose of this election audit analysis is to confirm the resutls of a local congressional elections. By writing a script that accesses the supplied .csv and quickly reads through the collected ballots, we can quickly determine various statistics, such as:
- The total number of votes cast.
- The count of votes received by each county.
- The percentage of votes casted by each county.
- The count of votes each candidate received.
- The percentage of votes each candidate received.

... which will also allow us to determine the winner of the election by popular vote.


## Election-Audit Results
<!-- Needs to be in a bulleted list.
How many votes were cast in this congressional election?
Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
Which county had the largest number of votes?
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Which candidate won the election, what was their vote count, and what was their percentage of the total votes? -->
As shown by the .txt file (analysis/election_results.txt) supplied by our script, we can determine that:
1. There were a total of 369,711 casted during this election.
2. Three counties participated in this election - Arapahoe (24,801 votes at 6.7%), Denver (306,055 votes at 82.8%), and Jefferson (38,855 votes at 10.5%) - with the most represented county being Denver.
3. There were three candidates that received ballots in the election:
   - Charles Casper Stockham, receiving 23.0% of the votes at a count of 85,213.
   - Diana DeGette receiving 73.8% of the votes at a count of 272,892.
   - Raymon Anthony Doane receiving 3.1% of the votes at a count of 11,606.
4. The winner of the election by popular vote is Diana DeGette.

## Election Audit Summary
<!--  In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election.
Give at least two examples of how this script can be modified to be used for other elections. -->
This script has a lot of potential for modularity depending on the needs of the commission or the information being collected from the ballots. The .csv provided only contained information about ballot IDs, counties, and nominated candidates. Though, if additional information was available this script can be modified to find other characteristics such as voter demographics, allowing for further analysis to be made. Along that line, we can also modify the script to determine patterns among these given characteristics, such as mapping the percentage of voters by county against each nominated candidate, allowing us to determine which candidate was the most popular within each county.
