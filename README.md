# Analysis of the Election Audit

## 1) Overview of Election Audit:

A Colorado Board of Elections employee has given you the following task to complete the election audit of a recent local congressional election.

* Calculate the total number of votes cast.
* Get a complete list of candidates who received votes.
* Calculatae the total number of votes each candidate received.
* Calculate the percentage of votes each candidate won.
* Determine the winner of the election based on popular vote.

After giving you an overview of the election audit tasks, we wants to go over the steps required in detail. Showing you a technique commonly used by programmers to write steps of their code, which is called `pseudocode`. Pseudocode will make the audit easier to present to nontechnical colleagues and stakeholders.

In this project, our final Python script will need to be able to deliver the following information when the script is run:

* Total number of votes cast
* A complete list of candidates who received votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote


## 2) Election-Audit Results:
> Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

* How many votes were cast in this congressional election?

> - **Total Votes Cast** in this congressional election was **369,711** 

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
> ***County Votes:***
> - **Jefferson** county has `10.5%` total percentage with a total votes of **38,855**
> - **Denver** county has the `82.8%` total percentage with a total votes of **306,055**
> - **Arapahoe** county has `6.7%` total percentage with a total votes of **24,801**

* Which county had the largest number of votes?
> ***County with Largest Number of Votes:***
> - **Denver** county has the largest number total of **306,055**
> - In addition, **Denver** county has the total votes percentage of `82.8%`  
> - **Denver** county is the Largest County Turnout

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
> ***Candidate Percentage of Votes:***
> - **Charles Casper Stockham** candidate has `23.0%` total percentage with a total votes of **85,213**
> - **Diana DeGette** candidate has the `73.8` total percentage with a total votes of **272,892**
> - **Raymon Anthony Doane** candidate has `3.1%` total percentage with a total votes of **11,606**

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
> ***Election Results:***
> - **Diana DeGette** won the election, with a total votes of **272,892**
> - In addition, **Diana DeGette** has the total percentage votes of `73.8%`  
> - **Diana DeGette** is the Winner.

* The information above was collected through using Python code to manipulate and analyze our data source: `election.csv`

* After running the code the terminal looks as follows:

![PyPoll_Terminal](https://github.com/vvinci21/Election_Analysis/blob/b03a68d7797eb7bd63fba99c7987e41d3994e02e/Resources/PyPoll_Terminal_SS%202.png)

* This information is then written and saved to the `election_results.txt` file. Below is a screen shot of the file.

![PyPoll Text Print Out](https://github.com/vvinci21/Election_Analysis/blob/c400b18d85f6774a3750e5cc93cb91922dcd4234/Resources/election_txt%202.png)

## 2) Election-Audit Summary:

* I would propse this code be source code for all future elections moving forward. With little modification a number of data can be extracted. 
* For example, turning this code into a usable script for a federl election one would need only to adjustt the county list and county dictionary from `county_options=[]` and `county_votes={}` to `state_options=[]` and `state_votes={}`. This change would then repeat throughout the scrpipt. 

* Script can also be modified to pull in other CSV files to determine if a bill was passed or a law that was voted on was voted in favor for or not. In this way the vote counter would work the same however we would have to change and modify the lists and dictionariies. 

