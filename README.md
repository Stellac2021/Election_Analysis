# Election_Analysis

## Overview of Election Audit
The Colorado Board of Elections has requested some data to complete the election audit
### Purpose
The goal is to use Python and retrieve data from the provided CSV file *election_results.csv* to deliver the below information requested from the election commission:

  - The voter turnout for each county
  - The percentage of votes from each county out of the total count
  - The county with the highest turnout

## Election Audit Result
Below are the election outcomes :triangular_flag_on_post::triangular_flag_on_post::triangular_flag_on_post:
- **Total votes** : There were **369,711** votes cast in the election.
    
### County Results

As shown below, **Denver has the largest number of votes** 

   - Jefferson: 10.5% (38,855 votes)
   - Denver: 82.8% (306,055 votes)
   - Arapahoe: 6.7% (24,801 votes)
    
### Candidate Results

**The winner** of the election was **Diana DeGette** who received **73.8%** of the votes and **272,892** votes
  - Charles Casper Stockham: 23.0% (85,213 votes)
  - Diana DeGette: 73.8% (272,892 votes)
  - Raymon Anthony Doane: 3.1% (11,606 votes)

:star2: **The election outcomes has been calculated with an output in Python with text file created as below**

![](Resources/election_results.png)


## Election Audit Summary
This script can be used to calculate the winner and voter turnout by county for any election. Some suggestion with the modification:

1. Currently the script is hard coded to certain columns. For example, the current code will only work when the county and candidate information is in the current rows. We could modify the script to get user input for which columns to analyze.

2. Currently the script is only limited to analyize county and candidate names. To be used for different types of election analysis, other variables such as states, cities, years and dates might needed be added on the script.

