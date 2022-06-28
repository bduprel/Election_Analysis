#Election Audit:

##Purpose of Audit:
The point of this audit was to get a complete count of the votes for each candidate and county. another goal was to calculate the percerntage of votes each canidate received and what percentage of votes came from each county. The final goal was to determine the winner of the election and what county had the highest voter turnout.

##Election Turnout:
The final turnout of the elections shows:

###Total Votes:
369,711

###County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

###Largest County Turnover:
Denver

### Canidate Vote Breakdown
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

### Winning Candidate Breakdown:
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

This was done by creating a vote counter as well as county and candidate lists and dictionaries. This allowed python to add new items to the list, and if those names were repeated, add a vote to that name. 

### Code example
![election_code_example](https://user-images.githubusercontent.com/106126621/176081134-c9637a6f-994f-44bb-b017-1e54540af975.png)
![election_code_example_2](https://user-images.githubusercontent.com/106126621/176081149-3f6b8525-ee48-41d2-bb8d-318f104fa1a8.png)

## Election Audit Summary:
This script can be easily expanded to use more counties or even states as well as handle a larger list of candidates. With even more adjustment, it could be used for a U.S. presidential vote and simulate the electoral college.
A possible example would be to create an extra variable, and use the county votes for a total U.S. state. Then each state could be given a value based on poulation. This would then be done for each state and those values would be totaled up to count the winner. 

It could also be swapped over for a company to get a vote of their most popular products and where they are most popualr at. By changing candidates to the products they sell and leaving the counties as they are, they would be able to tell where several of their customers are as well as the products they prefer.
