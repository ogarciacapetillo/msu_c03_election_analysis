# Election Analysis

## Project Overview
A Colorado Board of Election employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who receives votes.
3. Calcualate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.7, Visual Studio Code, 1.64.2

## Summary
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were:
    - Candidate 1 - Charles Casper Stockham
    - Candidate 2 - Diana DeGette
    - Candidate 3 - Raymon Anthony Doane
- The candidate results were"
    - Candidate Charles Casper Stockham received "23.0%" of the vote and "85,213" number of votes.  
    - Candidate Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
    - Candidate Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
- The winner of the election was:
    - Candidate 2 - Dianna DeGette, who received "73.8%" of the vote "272,892" number of votes.

## Challenge Overview
Additional requirements to present the following 

1. The voter turnout for each county and 
2. The percentage of votes from each county out of the total count
3. The county with the higest turnout


## Election-audit results

- How many votes were cast in this congressional election?

![TotalVotesElection](/Resources/Total_votes_election.png)

- Votes by County and respective percentage

![VoterByCounty](/Resources/County_votes.png)

- County with highest turnout

![CountyHighestTurnout](/Resources/Largest_county_turnout.png)

## Challenge Summary

This script analysis can be easily leverage to other congressional election commission, in order to adapt the script for other elections
would be sufficient to update the column index with the respective information if the columns are in different order to the respective file

Current columns order:

| Ballout Id | County | Candidate |

* Arrange columns in script respectively to the columns on the source file
