# PyPoll Challenge

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast in this congressional election.
2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
3. Determine the county with the largest number of votes.
4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
5. Determine the winner of the election based on popular vote, their vote count and their percentage of the total votes.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8, Visual Studio Code, 1.46.1

## Summary
The analysis of the election show that:

### Total Election Results
- There were 369,711 votes cast in the election.

### County Results
- The county results were:
    - Jefferson received 10.5% of the vote and 38,855 number of votes.
    - Denver received 82.8% of the vote and 306,055 number of votes.
    - Arapahoe received 6.7% of the vote and 24,801 number of votes.
- The county with the largest number of votes is Denver.

### Candidate Results
- The candidate results were:
    - Charles casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana Degette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

![PyPoll_Challenge_CommandLineResult](https://github.com/grwon/PyPoll_Challenge/blob/master/analysis/OutputToCommandLineResults.png)

## Election Audit Summary
- This script successfully provided insights for this congressional election. We were able to determine the results based on counties and also based on candidates. This script was well written such that the source code is easy to read, understand and maintain. There is good potential for this script to be utilize for future elections. A simple change to line 9 file_to_load variable can be easily amended to a new file and new path for the next year's election to retrieve the new source file instead of "election_results.csv" and the script will run successfully to read the new csv and perform the same analysis. Secondly, we can amend candidate_name variable to candidate_id string variable and the script will run to read the new csv file with candidate IDs. This simple change will allow you to perform analysis based on candidate IDs instead to keep result information anonymous. 
