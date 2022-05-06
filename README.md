# Election-Analysis

## Overview of Project
Seth and Tom are working with the election audit commission. They need a python program to analyze the election data and determine the winner while analyzing number of votes per candidate and county breakdown. The data set is relatively simple with just 3 data points per entry (Ballot ID, County, Candidate) but, very large with over 350k entries. This type of data set will work well with python.

### Purpose
The goal of this project is to verify the winner of election and analyze voting data by candidates and counties. 

## Analysis
We utilized python lists, dictionaries, loops, conditionals and reading/writing files. Only two python modules were imported, os and csv. These helped determined voter count and percentages for counties and candidates.

### Total Votes
There were 369,711 total votes cast across three candidates and counties. 

### County Breakdown
Below is a breakdown of county votes. This shows name of county, percentage of total votes and number of votes per county:
*Jefferson: 10.5% (38,855)
*Denver: 82.8% (306,055)
*Arapahoe: 6.7% (24,801)

### Highest County
Denver had the most votes per any county with a total of 306,055 and 82.8% of total votes. 

### Candidate Breakdown
Below is a breakdown of candidate votes. This shows name of candidate, percentage of total votes and number of votes per candidate:
*Charles Casper Stockham: 23.0% (85,213)
*Diana DeGette: 73.8% (272,892)
*Raymon Anthony Doane: 3.1% (11,606)

### Candidate Winner
Diana DeGette is the winner. She had 272,892 and 73.8% of total votes. 

## Results
This python script will easily work with other elections. It only needs two data points per entry (County and Candidate). The data set that was used only had three candidates and counties. However, the code is dynamic and won’t need to be updated if there are more candidates or counties. It is hardcoded to see county in column 2 and candidate in column 3. This could be modified to be dynamic and looks for specific headers anywhere in dataset. Another modification is analyzing the ballot id field. This will allow anyone to see if a vote was counted multiple times. There should be only one vote per id. 

