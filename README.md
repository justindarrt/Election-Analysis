# Election-Analysis

## Overview of Project
Seth and Tom are workign with the election audit commission. They need a python program to analyze the election data and determine winner while analyzing number of votes per candidate and county breakdown. The data set is relativly simple with just 3 data points per entry (Ballot ID, County, Candidate) but, very large with over 350k entries. This type of data set will work well with python.

### Purpose
The gaol of this project is to verify the winner of election and analyze voting data by candidates and counties. 

## Analysis
We utlized python lists, dictonraires, loops, conditionals and reading/writing files. Only two python modules were imported, os and csv. These helped determined voter count and percentages for counties and candidates.

### Total Votes
There were 369,711 total votes cast across three candidates and counties. 

### County Breakdown
Below is a breakdown of county votes. This shows name of county, percenatge of total votes and number of votes per county:
*Jefferson: 10.5% (38,855)
*Denver: 82.8% (306,055)
*Arapahoe: 6.7% (24,801)

### Highest County
Denver had the most votes per any county with a total of 306,055 and 82.8% of total votes. 

### Candidate Breakdown
Below is a breakdown of candidate votes. This shows name of candidate, percenatge of total votes and number of votes per candidate:
*Charles Casper Stockham: 23.0% (85,213)
*Diana DeGette: 73.8% (272,892)
*Raymon Anthony Doane: 3.1% (11,606)

### Candidate Winner
Diana DeGette is the winner. She had 272,892 and 73.8% of total votes. 

## Results
This python script will easliy work with other elections. It only needs two data points per entry (County and Candidate). The data set that was used only had three candidates and counties. However, the code is dyanmic and wont need to be updated if there are more candidates or counties. I reccomend one addiotnal analysis. we should analzye the ballot id field. This will allow to see if any vote was counted mutliple times. 
