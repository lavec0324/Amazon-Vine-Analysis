# Amazon Reviews
Module 16

## Overview of the Analysis
The purpose of this analysis is to determine based on tools review data whether or not there is a bias for a higher rating based on whether that rating is paid for or not.  We used amazon review data for tools that are stored in an AWS S3 bucket.  That data can be found at this link:



## Results

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
* After the initial filtering for total votes >= 20 and at least a 50% helpful votes to total votes, there were 31,737 reviews.
* Of those:
	* 285 were paid vine reviews
	* 31,452 were non-paid vine reviews

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* From the above filtered lists there were:
	* 163 were 5 star ratings for paid vine reviews
	* 14,603 were 5 star ratings for non-paid vine reviews

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* From the above 5 star ratings:
	* 57.2% were paid reviews
	* 46.4% were non-paid reviws

##Summary 

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.









<!--

Purpose of this project was to analyze several sources of employee data from Pewlett-Hackard and determine as they look toward to succession planning.  We will be looking at the number of retiring employees by their title and see where potential gaps exist and where that may be filled by looking at mentorship opportunities within the company.  This may help the company determine if the voids that are left by retiring employees can be filled by training within the company.

## Results

From the tables below we can see:

* PH has a disproportionate population of senior personnel retiring which includes engineers and staff
* There is a very small population of managers retiring
* Overall numbers of mentors is small relative to the retiring staff which would be an issue as even with one person have several mentorees they would still not be able to cover the retiring population
* That disproportion gets even greater when looking at the senior engineers, where potential mentors are outnumbered by retirees by over 150 to 1

#### Retirement eligible grouping by title:

![](https://github.com/lavec0324/Pewlett-Hackard-Analysis/blob/main/Resources/retiring_titles.PNG)

#### Mentorship eligible grouping by title:

![](https://github.com/lavec0324/Pewlett-Hackard-Analysis/blob/main/Resources/mentor_eligible.PNG)

## Summary

Specifically answering two questions asked:

* How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  * 72,458 roles will need to be filled if all eligible retirees are to be replaced
* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  * No, based on the current criteria, the number of mentors are far overshadowed by the number of retiring employees.

Additional queries could include:

* Count of number of employees in the retirement table to simplify summing up the number of employees eligible for retirement.
* Increase the date ranges of the mentors to expand the population of mentors.
* Group by counts on mentors (already included but not originally requested)
* Could also create queries to see what other roles were performed by employees, not just the current role, to see if mentorship can be expanded where gaps exist.


-->