
 **2** Python Challenges: PyBank and PyPoll.

## PyBank

![Revenue](Images/revenue-per-lead.jpg)

* A Python script for analyzing the financial records of a mock company. Analyzes financial data[budget_data.csv](/Resources/budget_data.csv). The dataset is composed of two columns: `Date` and `Profit/Losses`. 

* The Python script analyzes the records to calculate each of the following:

  * The total number of months included in the dataset

  * The total net amount of "Profit/Losses" over the entire period

  * The average change in "Profit/Losses" between months over the entire period

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in losses (date and amount) over the entire period

* As an example, the analysis should look similar to the one below:

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

* In addition, the final script should both print the analysis to the terminal and export a text file with the results.

## PyPoll

![Vote-Counting](Images/Vote_counting.jpg)

* A python script that analyzes poll data called [election_data.csv](Resources/election_data.csv). The dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`. This Python script analyzes the votes and calculates each of the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.

* As an example, the analysis should look similar to the one below:

  ```text
  Election Results
  -------------------------
  Total Votes: 3521001
  -------------------------
  Khan: 63.000% (2218231)
  Correy: 20.000% (704200)
  Li: 14.000% (492940)
  O'Tooley: 3.000% (105630)
  -------------------------
  Winner: Khan
  -------------------------
  ```

* In addition, the final script should both print the analysis to the terminal and export a text file with the results.

## Additional Notes

* Script can import modules like `csv`; to read and write files in various formats; store contents in variables, lists, and dictionaries; iterate through basic data structures; and can debug along the way. 

* The datasets are quite large. This was done purposefully, as it showcases one of the limits of Excel-based analysis. While our first instinct, as data analysts, is often to head straight into Excel, creating scripts in Python can provide us with more robust options for handling "big data".


## Copyright

Trilogy Education Services © 2018. All Rights Reserved.