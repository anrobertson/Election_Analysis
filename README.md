# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given me the task of reporting the total number of votes casted, the total number of votes for each candidate has received, the percentage of votes for each candidate and the winning candidate based on the popular vote through the power of Python. 

## Summary
### Candidate Votes
* Calculate the number of votes cast:
  * Through this project, I have calculated that the amount of votes that has been casted was 369,711.
* Get a complete list of candidates who received votes.
  * The three candidates who received votes were: 
  * Charles Casper Stockham
  * Diana DeGette 
  * Raymon Anthony Doane
* Calculate the total number of votes each candidate won.
  * Charles Casper Stockham received ***23.0%*** of the votes with 85,213 votes.
  * Diana DeGette received ***73.0%*** of the votes with 272,892 votes.
  * Raymon Anthony Doane received ***3.1%*** of the votes with 11,606 votes.
* Determine the winner of the election based on the popular vote.
  *The winner of the election based on the popular vote is Diana DeGette who won ***73.*%*** of the vote with the winning vote count of 272,892

## Resources
* Data Source: election_results.csv
* Software: Python 3.6.1, Visual Studio Code, 1.38.1
  
## Challenge Overview
I was given the task to automate the  of this information through Python and find the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout! Unfortunately my code is only showing one county but from what I gathered, in  the CSV file, it is divided by columns. The Ballot ID would be 0 while the County would be considered 1 which is why I placed that number in the county list.
### My input
![](Resources/countynameinput.png)
### Reasoning
![](Resources/countynameinput2.png)
### Start of for loop
I then used a for loop to go through my data and retrieve the county vote.

![](Resources/retreivecountyvote.png)
### Float
Next I calculated the percentage of county votes using the float attribute.

![](Resources/float.png)

I then saved the results over to the txt_file!

### County Votes
My results for county votes were not labled correctly, however, I got the percentage and the largest county turnout correct.
* County Votes (In my code, the output shows as Araphoe but I will label what it is suppose to be.)
  * Arapahoe (Jefferson): 10.5% (38,855)
  * Arapahoe (Denver): 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
* Largest County Turnout: Denver

## Election-Audit Summary
This code can be used and altered with different csv files. For example, if you wanted to track nationwide elections and add each state, you would have to make sure your CSV file has states within it and extarct from each row and loop through it. If you wanted to find the parties that they voted under, you would creat a "party" section and also extract from that row.
