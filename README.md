# Election-Analysis

## Project Overview
A colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congresional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on populare vote.


## Resources
-Data Source: election_results.csv <br/>
-Software: Python 3.11.0, Visual Studio Code 2


## Summary
![ScreenShot](https://github.com/ChristinaRich/Election-Analysis/blob/b9ad1569e015e899c4582f6427bd6b1d6eb02b2a/Election%20Results%20image.png)
<br/>
### The analysis of the election shows that:<br/>
<br/>
There were 369,711 votes cast in the election.<br/>
<br/>
The counties involved were:<br/>
  - Jefferson County, which cast 10.5% of the votes and 38,855 number of votes.<br/>
  - Denver County, which cast 82.8% of the votes and 306,055 number of votes.<br/>
  - Arapahoe County, which cast 6.7% of the votes and 24,801 number of votes.
<br/>
  - The county with the largest turnout was Denver County.<br/>
<br/>
The candidates were:<br/>
  - Diana Degette<br/>
  - Charles Casper Stockham<br/>
  - Raymon Anthony Doane<br/>
  <br/>
The candidate results were:<br/>
  - Diana Degetter received 73.8% of the vote and 272,892 number of votes.<br/>
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.<br/>
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.<br/>
  <br/>
The Winner of the election was:<br/>
  - Diana Degette, who received 73.8% of the vote and 272,892 number of votes.<br/>
  
## Election Audit Summary
<br/>
This python code can be useful in future elections with a few modifications. It might be more useful for neighborhood canvasing if the data from the ballot includes more local locational information than the county. If a candidate knows the data for a region of the county, they know where they need to focus their efforts. If we show neighborhood x of Jefferson County voted for candidate Y, and this was the difference between winning and losing, candidates can focus their efforts more specifically. We can alter the script to print results within the county. <br/>
<br/>
We can also alter the script to show the change over time. If we had data from two or more sequential elections, our script could run through each election dataset as we have in this analysis, and then we could compare the variables to show trends. For instance, the % of votes obtained by the winning party increased or decreased during the time period. 
