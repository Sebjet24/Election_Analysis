# Election_Analysis

## Overview of Election Audit

### Purpose:

 - After creating a successful election audit for Seth and Tom, the election commission has requested some additional data to complete the audit. Specifically they asked for the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. Using the [election_results.csv](https://github.com/Sebjet24/Election_Analysis/files/7575194/election_results.csv) once again, I will compile the data and outline the key information that they are searching for using Visual Studio and the Python language.

## Election-Audit Results

### Addressing how I got each Outcome

With the use of Python coding each outcome was easily produced. 

 - The total votes cast during the congressional election was 369,711. The code I used to find this number was a "for loop" going through each persons vote and adding a 1 to the total:

![Screenshot (19)](https://user-images.githubusercontent.com/91230277/142739538-301f6e86-7d85-4aa0-a9b2-94aa63b922b4.png)

 - The results of each County vote are as follows:

![Screenshot (21)](https://user-images.githubusercontent.com/91230277/142739738-6200836d-2d3b-4b18-adca-10aaef92de95.png)

 - Now each county vote was a bit more tricky to code than the total vote, but it still consisted of adding to the total of each county within the same "for loop". I also distinguished each vote to each county with an "if statement":

![Screenshot (20)](https://user-images.githubusercontent.com/91230277/142739671-326a26af-28a6-4fbd-acff-577404e5502d.png)
![Screenshot (22)](https://user-images.githubusercontent.com/91230277/142739809-b449da5a-5034-462e-b1c0-242d19206535.png)

 - The county that recieved the most votes was Denver. I determined the largest quantity of votes by using an if statment:

![Screenshot (23)](https://user-images.githubusercontent.com/91230277/142739830-e4561053-cc5c-4554-8c5f-cf6a3caf9b21.png)

 - I did a similar process of coding for the votes and percentages of the total votes each candidate received as I did for the county votes shown below:

![Screenshot (24)](https://user-images.githubusercontent.com/91230277/142740068-c23e3f34-8a9f-420f-9ca2-35b330b3bfb7.png)
![Screenshot (25)](https://user-images.githubusercontent.com/91230277/142739937-3cb2495e-e53a-4450-9e7d-5cb35bb8d5ba.png)

 - Finally, the winner was Diana DeGette with a wopping 272,892 votes and a 73.8% portion of the votes cast. I did another "if statement" to determine this:

![Screenshot (26)](https://user-images.githubusercontent.com/91230277/142740022-7f685bd0-8993-4963-afc7-343b09efbd8b.png)
![Screenshot (28)](https://user-images.githubusercontent.com/91230277/142740037-b174f8ea-d394-417a-9985-52afa755933b.png)

## Election-Audit Summary

### Final Thoughts and Proposal

 - As requested, I created a python program that showed the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. I also showed the winner of the congressional election and deteremined her results in comparison to the other candidates.
 - With this all being said, I know that this code can do the same for other elections not just for this one. This code easily and smoothly can comb through any csv file with results structured similarly to [election_results.csv](https://github.com/Sebjet24/Election_Analysis/files/7575194/election_results.csv). But even still I could easily add to this script with very little effort since the base coding structure is already there. 
 - For example, if you wanted to compare these results to past elections I could simply add to the end of the coding to take into account past elections and compare winning perecentages. This could give us a better outlook on this election and why it went the way it did.
 - A second example is we could add another column of data with their registered political party and then determine the percentage of people that voted for candidates in correlation to their political party. But why stop there. We could take in all kinds of information and look at the data to help determine reasons why people voted the way that they did.
 - In conclusion, I would like to propose using this code for future elections and building upon it to take in more information so that we can get a better look at why elections went the way that they did.
