# Election Analysis

## Overview
In this project, we are asked to assist with an election audit of a local congressional election provided by the Colorado Board of Elections. The board has asked for additional information, and they were interested in voter turnout for each country, the percentage of votes from each county, and the county with the highest turnout. The board also requested an analysis of the election results and a business proposal on how to use the script in future elections.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.13 , Visual Studio Code: 1.68.1

## Results
The image below shows the output of my code and it shows the total votes, each county votes, each candidate votes, and the winning candidate information.

![Results](https://user-images.githubusercontent.com/106292020/174050934-8e70cc9d-f31f-46cc-8e62-75072f5bc2a4.png)

To produce the county outputs, I followed the same coding structure that was used in the candidates for loop and if statements but using county-related name variables. To print the output into the terminal and text file there was a slight difference in using "\n". 
### Election outcome
- There were total of 369,711 in this congressional election.
- County Breakdown
  - Jefferson had 10.5% of the total votes with 38,855 votes.
  - Denver had 82.8% of the total votes with 306,055 votes.
  - Arapahoe had 6.7% of the total votes with 24,801 votes.
- The county with the largest votes was Denver.
- Candidate Breakdown
  - Charles Casper Stockham had 23.0% of the total votes with 85,213 votes.
  - Diana DeGette had 73.8% of the total votes with 272,892 votes.
  - Raymon Anthony Doane had 3.1% of the total votes with 11,606 votes.
- The winning candidate was Diana DeGette with a vote count of 272,892 and she had 73.8% of all votes.

## Summary
My codes can be used and modified by the election board for audits of past and future elections. A CSV file must contain both the candidate and the county name  for any output to be generated. The board would have to modify the code if the counties or candidates are located in a different column by changing the index inside the bracket (e.g. if the candidate column is in column D of the CSV file, then an example code would be "candidate_name = row[3]"). Another way the code can be used or modified is if different results are needed. The board can modify the variables' names to make it more consistent with the word "age" or use similar coding syntax to create additional for-loops and if statements.
