# Election_Analysis

## Project Overview
I was given the task of doing an Election audit for the Colorado Board of Elections for a local congressional race.

### Audit Process Overview
1. Determined total vote count for the congressional race.
2. Determined the list of candidates in the race. 
3. Computed the total votes received per candidate.
4. Calculated what percentage of votes each candidate received. 
5. Deduced the winner of the election based on the popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code

## Summary
In iterating through all of the data in the election_results.csv, these are my conclusions. 

The total vote count for this election was 369,711 votes cast. 

There were three total candidates in this race.
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane

The breakdown of the vote counts is as follows. 
  - Raymon Anthony Doane received 11,606 total votes with 3.1% of the total vote count. 
  - Charles Casper Stockham received 85,213 total votes with 23.0% of the total vote count. 
  - Diana DeGette received 272,892 total votes with 73.8% of the total vote count. 

The winner for the election, by a landslide was Diana DeGette receiving the highest number of votes and highest percentage of votes. 

## Challenge Overview
I was given the additional task of examining voter turnout by county to determine to total vote count and percentage of total votes. 
1) Determined the list of counties to evaluate
2) Computed total votes cast per county. 
3) Calculated what percentage of votes were received in each county. 
4) Determined the county with the highest turnout based on percentage of votes cast.

## Challenge Summary
In examining all of the data by county in the election_results.csv file, this is what I determined:

There were three counties with turnout in this race. 
  - Jefferson
  - Denver
  - Arapahoe

The breakdown of the county turnout is as follows. 
  - Arapahoe received 24,801 total votes with 6.7% of the total vote count. 
  - Jefferson received 38,855 total votes with 10.5% of the total vote count.
  - Denver received 306,055 total votes with 82.8% of the total vote count. 

The county with the biggest turnout was Denver with a huge margin over the other two counties. Way to go Denver!

## Election Audit Summary
This project was a breeze by using the Python Script to determine these statistics. I was able to reformat the code used for the Candidate results to easily determine the turnout by county. It was key in quickly looking at the large amount of data and giving me an easy way to summarize the campaign results with a click of a button. 

### Additional uses for the Python Script
Here are some other statistics that this script can be used for in future elections. 
 
#### Voting Method
In this election, there were 3 methods of voting: Mail in ballots, Punch Cards and DRE. I believe that if we could access the data showing the voting method, we could calculate the breakdown percentage of voting method to determine on average how people tend to vote. Depending on the breakdown, the Colorado Board of elections can determine how best to staff their Voting Locations. For areas with more mail-in ballots, they can possibly shift polling locations to areas with higher in person voting techniques. 

#### County Turnout Trend
If you continue to use this Python Script in the future, you can get a sense of turnout trends. If you were to look at multiple years of voting data, you could create an additional Data Dictionary that adds in the year of the campaign to get a sense of how voter turnout changes year over year. This could give the Colorado Board of Elections a chance to see how the overall voter count and percentage changes over the years. 

#### Political Party Breakdown
You could also examine Political Party voter percentage. If you were able to look at which Political Party the candidates are associated with, you could look at Political Party voter breakdown as well. If you have multiple years of data, you can see the voter trend. 


