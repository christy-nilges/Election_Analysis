# Election_Analysis

## Overview of Election Audit
A Colorado board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes case.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the total number of votes for each county.
5. Calculate the percentage of votes each candidate won.
6. Calculate the percentage of votes for each county.
7. Determine the winner of the election based on popular vote.
8. Dtermine the county with the largest turnout.

## Resources
- Date Source: election_results.csv
- Software: Python 3.8.8, Visual Studio Code, 1.59.1

## Election-Audit Results
The analysis of the election show that: 
- There were **369,711** votes case in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    -  Charles Casper Stockham received **23.0%** of the vote and **85,213** number of votes.
    -  Diana DeGette received **73.8%** of the vote and **272,892** number of votes.
    -  Raymon anthony Doane received **3.1%** of the vote and **11,606** number of votes.
- The winner of the election was:
    -  Diana DeGette, who received **73.8%** of the vote and **272,892** number of votes. 
- The county results were:
    -  Jefferson had **10.5%** of the votes and **38,855** number of votes
    -  Denver had **82.8%** of the votes and **306,055** number of votes
    -  Arapahoe had **6.7%** of the votes and **24,801** number of votes
- The county with the most turnout was:
    -  Denver, who had **82.8%** of the votes and **306,055** number of votes

            Election Results
            -------------------------
            Total Votes: 369,711
            -------------------------
            County Votes:
            Jefferson: 10.5% (38,855)
            Denver: 82.8% (306,055)
            Arapahoe: 6.7% (24,801)
            --------------------------
            Largest County Turnout Denver
            ---------------------------
            Charles Casper Stockham: 23.0% (85,213)
            Diana DeGette: 73.8% (272,892)
            Raymon Anthony Doane: 3.1% (11,606)
            -------------------------
            Winner: Diana DeGette
            Winning Vote Count: 272,892
            Winning Percentage: 73.8%
            -------------------------
 
## Election-Audit Summary

Expanding the Election Audit to include voter turnout by county with candidates results has been a great way to take advantage of the convenience a script provides. The added insight can be a template for future election performance, so that you may properly allocate resources where turnout is low or demographics are hard to reach.

A little time invested into customizing the script can provide on-demand analysis for years to come.

Modifying the script to produce turnout results by county is just one of many ways that minor adjustments to the code can reveal critical data. For example, we could also dive deeper and determine what percentage of each county voted for each candidate by adding an if-statement to the code. These type of Decision Statements are how the code runs calculations and all we've done is provide it with a data file.

Similarly, if this were a federal election, we could use the same script and change the county to states.

The script used to perform the Election Audit can be a valuable resourse for any election scenario; county or state.





