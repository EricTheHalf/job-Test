Notes - still to complete:

Some of the output formatting is very basic

Command line parameters to be directed using locals()



# This is the test definition
# Rules
An email with the link to your solution must be sent to ml@bink.com within 48 hours of receipt of the test. The contents must include:
Deliverables:
A link to a public Git repository with your final code.
Guidelines:
1.	To help understand how you approach the problem we will assess your use of source control, how you built up to the final solution and what was committed along each step. 

2.	The code must be written in Python 3. You may use any framework or libraries to complete this task, except for data analysis libraries like Pandas. We prefer to see how you handle each task.

3.	Unit tests must be provided to cover your code.
Objective
Data File To be Used:
Dataset source: https://data.gov.uk/dataset/mobile-phone-masts
(The attached CSV contains publicly available data about mobile phone masts in an area of the UK.
Contains public sector information licensed under the Open Government Licence v3.0.

Dataset description:
This dataset provides information on mobile phone masts located on Leeds City Council property, respective lease information and annual rent charges concerning them.

NOTE:
This is real life dataset and contains un-normalised data, for example the Tenant Name field contains several very similar names, treat these as individual names.

Actions:
1.	Load the data file, process and output the data in the forms specified.
2.	Read in, process and present the data as specified in the requirements section.
3.	Demonstrate usage of list comprehension for at least one of the tasks.
4.	Allow user input to run all your script, or run specific sections. For example, just display section3 in the requirements below.


# Requirements
1. Read in the attached file and produce a list sorted by Current Rent in ascending order . Obtain the first 5 items from the resultant list and  output to the console.

2. From the list of all mast data create new list of mast data with Lease Years = 25 years.
  Output the list to the console, include all data fields.
Output the total rent for all items in this list to the console.

3. Create a dictionary containing tenant name and a count of masts for each tenant. Output the dictionary to the console in a readable form.
NOTE. Treat "Everything Everywhere Ltd" and "Hutchinson3G Uk Ltd&Everything Everywhere Ltd" as separate entities.

4. List the data for rentals with Lease Start Date between 1 June 1999 and 31 Aug 2007.
Output the data to the console with dates formatted as DD/MM/YYYY.

Assessment
Your code will be reviewed and assessed according to the following:
1. Adherence to requirements.
2. Code quality – readability and structure of code.
3. Unit test coverage and relevance of the tests.
Helpful Tips
If you struggle completing the test or have concerns over certain aspects that is okay – just highlight it to us when you submit your test. Explain what you couldn’t get working and steps you took to solve the problem. Whilst we want to see completed tests it is just as important for us to see how you approached an issue and attempted to find a solution.

Do not overthink your solution. Keep it simple and use what you know.

Write tests only for your code.

Don’t forget the ReadMe

Avoid creating additional requirements.

# __________________________________________________________

most recent data set at the url given above is

https://datamillnorth.org/download/mobile-phone-masts/f027f462-3621-4dba-8917-dc35d70a0fb2/Mobile%2520Phone%2520Masts%252001.04.2019a.csv
