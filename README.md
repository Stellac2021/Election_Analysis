# Election_Analysis

## Overview of Election Audit
The Colorado Board of Elections has requested some data to complete the election audit
### Purpose
The goal is to use Python and retrieve data from the provided CSV file *election_results.csv* to deliver the below information requested from the election commission:

  - The voter turnout for each county
  - The percentage of votes from each county out of the total count
  - The county with the highest turnout

## Election Audit Result
Below are the election outcomes
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

1. The current dataset from the CSV file only has the county information. To analyize other election data, we could add state or city datasets for a broader or more detailed analysis.

2. It would be better to include the date, month and year of the election into the dataset in order to conduct the election analysis in a more comprehensive perspective.

