# Election-Analysis
Auditing Colorado Election for local congressional election. 
## Overview of Election Audit
The purpose of this election audit is to analysize the total number of votes, number of voter turnout in each county, percentage of votes from each county out of the total count, county with the highest turnout, number of votes and percentage of votes each candidates and the statistic of the winner candidate. 
## Election-Audit Results
### Setting up our inital data file 
First by adding a variable "file_to_load" we load a data file from a path that we will be working with to get the election results. Then by creating a variable "file_to_save" we created a path to a text file where we will save our data analysis result. 

![file_to_load](Screenshots/file_to_load.png)

### The codes used in the analysis
![13-39](Screenshots/13-39.png)
![39-74](Screenshots/39-74.png)
![75-109](Screenshots/75-109.png)
![110-144](Screenshots/110-144.png)
![144-160](Screenshots/144-160.png)

## Results
* ### How many votes were cast in this congressional election?

There were total votes of 369,711

* ### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

There were three counties in the election data. The counties were Jefferson, Denver, and Arapahoe. The county with the highest number of votes is Denver with 306,055 votes, which is 82.8% of the total votes. The second highest county votes is Jefferson with 38,855 votes, which is 10.5% of the total votes. The third is Arapahoe with 24,801 votes, which is 6.7% of the total votes.

* ### Which county had the largest number of votes?

The largest county turnout is Denver.

* ### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

The three candidates in this election race were Charles Casper Stockham, Diana DeGette and Raymon Anthony Doane. The candidate Diana DeGette has the most votes with 272,892 count which is 73.8% of the total votes. The second most voted candidate is Charles Casper Stockham with 85,213 votes which is 23% of the total votes. In the third place, candidate Raymon Anthony Doane received 11,606 votes which is 3.1% of the total votes.

* ### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

The winner candidate was Diana DeGette with the vote count of 272,892 which was 73.8% of the total vote. 


![election_analysis_text_file](Screenshots/election_analysis_text_file.png)

## Election-Audit Summary

Working with big election data it is necessary to use the right tool to count the votes of the candidates and the county with accuracy and efficiency. By using this programming tools and script made in Python and VSC, the election commission could utilize in analyzing other elections in different year or counties with some modifications.  

### Example 1 
By downloading a new set of data file(.csv) in the Resources folder, the election commission can replace the data need to analyze in the line 
???file_to_load = os.path.join(???Resources???, ???new_data.csv ???)

### Example 2

If the election commisssion team is dealing with federal election data, the script can be changed from county to states. 
For example: The county_list = [] and county_votes = {} could be changed to states_list = [] and states_votes {}
county_list=[]
county_votes = {}

This Python script is the fundamental tool that can be used with any election with simple modification. It can be used to analyze larger data set with more votes or to analyze Federal level election. The script is ready to use and is written with precision in mind. Please reach out for further consultation if the election commission team is interested in utilizing this election analysis tool. 
