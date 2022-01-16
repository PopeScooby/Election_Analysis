# stock-analysis

## Overview of Project

### The purpose of this analysis is to examine a set of election results to deterine a couple different things. First we wanted to figure out how many votes each candidate received in the election and use that data to determine a winner. Secondly we wanted establish how many votes were cast in each of the couties in the dataset, and which county represented the most votes.

## Election-Audit Results
![Election Results](Resources/TerminalPrintout.png)

### In order to analyze this election we used a dataset consiting of only three columns of data. A Ballot ID, Which County the ballot was cast in, and who the ballot was cast for. This data can be used to determine the winner of the election as well as other interesting information. Below you can see some of the conclusions we can make, and I will explain how I calculated it.
  -  All of the analysis here was achived by looking at the data in the data set line by line. Since each line represnts a vote, by counting the number of lines we look at we are also counting the number of votes. I simply created a variable at the beginning of the algorithm called total_votes and set it to 0 (line 14[^1]: total_votes = 0). Then everytime the program looked at a new line it added one to that total_votes (line 46[^1]: total_votes = total_votes + 1). Doing this told us the total number of votes cast was **369,711**
  -  There were **3** different counties in which votes were cast: Jefferson, Denver, Arapahoe. 
     * **Jefferson** received **38,855** votes, for **10.5%** of the total votes cast 
     * **Denver** received **306,055** votes, for **82.8%** of the total votes cast 
     * **Arapahoe** received **24,801** votes, for **6.7%** of the total votes cast
  -  By far **Denver** received the represented the most votes, with **82.8** percent of the toal votes cast, or **306,055** votes.
  -  There were **3** different candidates in this election for whom votes were cast: Charles Casper Stockham, Diana DeGette, Raymon Anthony Doane. 
     * **Charles Casper Stockham** received **85,213** votes, for **23.0%** of the total votes cast 
     * **Diana DeGette** received **272,892** votes, for **73.8%** of the total votes cast 
     * **Raymon Anthony Doane** received **11,606** votes, for **3.1%** of the total votes cast
  -  **Diana DeGette** was the clear winner of this election, with **73.8%** of the total votes cast going to her. That's **272,892** votes that she received.

[^1]:  refers to file PyPoll.py

## Summary

  Re
