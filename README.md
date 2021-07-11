# Election Analysis

# Project Overview - Election Audit
The election commission has requested some additional data to complete the election audit:

The voter turnout for each county
The percentage of votes from each county out of the total count
The county with the highest turnout

Using our python code we will add for loops and conditional statements with membership and logical operators to find the requested results. The results will then be printed to the command line and our election_results.txt file.


## Resources
-  Data Source: election_results.csv
-  Software:  Python 3.6.7, Visual Studio Code, 1.57.1


# Challenge Summary


##  Election-Audit Results:

<img width="302" alt="Deliverable 1" src="https://user-images.githubusercontent.com/691355/125178421-93bfd280-e199-11eb-88f0-be6ac5151b31.png">

-  **How many votes were cast in this congressional election?**

   
   The total amount of votes for the congressional election was 369,711.<br/>


-  **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**


   
   Jefferson county had 10.5% of total votes with 38,855 votes, Denver had 82.8% of total votes and 306.055 votes and Arapahoe had 6.7% of total votes and 24,801      votes.<br/>



-  **Which county had the largest number of votes?**

   
   The county which had the largest number of votes was Denver with 306,055.


-  **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**

   
   The candidates for the election were Charles Casper Stockham, Diana DeGette and Raymond Anthony Doane.  
   
   Charles Casper Stockham had 85,213 votes which was 23% of the total votes cast.
   
   Diana DeGette had 272,892 votes which was 73.8% of the total votes cast.
   
   Raymond Anthony Doane had 11,606 votes which was 3.1% of the total votes cast.



-  **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**
    
  
   The winning candidate of the election was Diana DeGette.  Diana had 272,892 votes which was 73.8% of all votes cast for the election.
   
   

## Election-Audit Summary: 

Modifications to this script can be made to accomadate the election commissions future needs.  One way this script can be altered is by adjusting the script to grab data from additional columns.  

<img width="474" alt="Screen Shot 2021-07-10 at 4 49 25 PM" src="https://user-images.githubusercontent.com/691355/125178981-cae4b280-e19e-11eb-8067-ae02e2ec77e7.png">

This would be useful if the election commissions wanted to compare county data by year.  Adding a year column into the csv and comparing previous year results may help the commission in identifying voter trends.

The election commission would also benefit if they wanted to compare voting acorss each state.  The script modification would be an added list and dictionary for state names and state votes.

<img width="362" alt="Screen Shot 2021-07-10 at 5 25 13 PM" src="https://user-images.githubusercontent.com/691355/125179570-38dfa880-e1a4-11eb-9cbd-69cd2044c238.png">

We would follow a similar process to the one we did for adding county names and county votes but adjust to provide statewide data.  We could then adjust our formula to include the total population of a state and use this to evaluate voter turnout during the election across each state.
