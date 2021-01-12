# ***Election Analysis***

## **Overview of Election Audit**
A Colorado Board of Elections employye asked for my help to complete an election audit of a recent local congressional election. I need to complete the following tasks:

1. Calculate the total number of votes cast.
2. Calculate the voter turnout for each county.
3. Calculate the percentage of votes from each county out of the total count
4. Get the name of the county with the highest turnout.
5. Get a complete list of candidates who received a vote.
6. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.

## **Resources**
To complete this task, I used the following:
- Data source: 
  - election_results.csv
  
- Software: 
  - Python, 3.7.6 64 bit 
  - Visual Studio Code, 1.52.1

## **Election Audit Results**
The analysis of the election show that:
  - There were 369,711 votes cast in the election.
  
  - The voter turnout for each county was:
    - Jefferson county: 38,855 votes.
    - Denver county: 306,055 votes.
    - Arapahoe county: 24,801 votes.
    
 - The percentage of voter turnout for each county are as follows:
    - Jefferson county: 10.5% with 38,855 votes of 369,711 total votes.
    - Denver county: 82.8% with 306,055 votes of 369,711 total votes.
    - Arapahoe county: 6.7% with 24,801 votes of 369,711 total votes.
 
 - The county with the largest turnout in thes congrssional election was Denver.
    
  - The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
    
  - The candidate results were:
    - Charles Casper Stockham received 23.0% and 85,213 votes.
    - Diana DeGette received 73.8% and 272,892 votes.
    - Raymon Anthony Doane received 3.1% and 11,606 votes.
    
  - The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## **Election-Audit Summary**

Working with this script, we can modify it by adding code lines to get the difference between the winner candidate and the runner up candidate to establish by how much the winner candidate won the election. This will be helpful especially in the instances where the election is very close.

By adding more data, such as the total registered voters, we can calculate the percentage of voters that voted on the election with respect of the total number of registered voters. This data can be presented as a whole, that is including all counties, and it can also be broken down by county. This will give more insight on the voting trends according to the population registered to vote.


