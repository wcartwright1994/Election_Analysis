
# Election_Analysis
Performing analysis to audit a recent local congressional election in Colorado.

**Overview of the Election Audit**

The purpose of this analysis audit is to:
1. Determine a list of candidates and counties that voted.
2. Calculate the total number and percentage of votes received by eaach candidate and cast per county.
3. Determine the county with the most number of votes cast.
4. Determine the winner of the election based on which candidate had that largest number of votes.

**Election Audit Results**

Based on the "election_results.csv" file provided the results of the election audit are as follows:
* 369,711 votes were cast
* County Results include:
	* Jefferson: 10.5% of the total vote (38,855 votes)
	* Denver: 82.8% of the total vote (306,055 votes)
	* Arapahoe: 6.7% of the total vote (24,801 votes)
* Denver County had the largest number of votes with 306,055.
* Candidate Results include:
	* Charles Casper Stockham: 23.0% of the total vote (85,213 votes)
	* Diana DeGette: 73.8% of the total vote (272,892 votes)
	* Raymon Anthony Doane: 3.1% of the total vote (11,606 votes) 
* Diana DeGette was the winner of the election with 73.8% of the votes (272,892 votes)

![Election_Results](https://user-images.githubusercontent.com/82549092/117600619-47650180-b11a-11eb-93bd-a27cc68f542c.png)

**Election Audit Summary**

The script provided can be used as a quick way to tally election running counts and final results. In addition, the script can be used to double check hand-counting to ensure the results align within an allowable difference.

Two ways this script can be modified are:
1. Save aggregated results in a flat table format to ensure that the results can be easily compared to previous and future elections.
2. Use matplotlib and add additional demographic detail to the data to allow candidates to easily visualize results to understand which areas/groups they should be targeting in future elections. 
