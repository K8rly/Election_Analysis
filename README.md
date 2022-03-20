Election_Analysis

## Election Analysis Overview
A Colorado Board of Elections employee needs to submit an election audit of a recent local congressional election to the election commission. The following tasks were requested:

 - Calculate the total number of votes cast.
 - Get a complete list of candidates who received votes.
 - Calculate the total number of votes each candidate won.
 - Calculate the percentage of votes each candidate won.
 - Determine the winner of the election based on popular vote.

## Resources
 - Data Source: election_results.csv
 - Software: Python 3.7, Visual Studio Code, 1.65.2

## Election Audit Results

### The election analysis showed that:
There were 369,711 total votes cast in the election.
The candidates were:
 - Charles Casper Stockham
 - Diana DeGette
 - Raymon Anthony Doane

### The county vote results were:

 - Jefferson: 10.5% (38,855 votes)
 - Denver: 82.8% (306,055 votes)
 - Arapahoe: 6.7% (24,801 votes)

### The county with the largest number of votes was:
 - Denver

### The candidate results were:
 - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
 - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
 - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

### The winner of the election was:
 - Diana DeGette who received 73.8% of the vote and 272,892 number of votes.

## Election Audit Summary
The script used for this election audit was modifed from its original version to incorporate county data as well as candidate data. The current script yielded results from three candidates and three counties, but the scripts can be modified for future elections to incorporate additional candidates or additional counties as needed. The script can also be modified to show lowest number of votes, lowest county turnout, or a possible tie.