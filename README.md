Data-Engineering-Test
=====================

This is a data engineering test.  Take as long as you need or you think is
reasonable. You don't need to complete all the requirements if you are pushed
for time, however your solution should give us enough code to confirm that you
are a skilled engineer.

You should use [python](https://www.python.org/) and
[PostgreSQL](https://www.postgresql.org/), with whatever libraries or
frameworks are appropriate.  Please note we’ll need to be able to
replicate and run your solution, so make sure to include information on how you set up the database, all your scripts and any migrations, imports etc.

Please do not make your solution publicly available, just compress this folder
and send it back to us.

**Feel free to ask any questions about the test, the data or your solution.**

Understanding Prices in London
------------------------------

We would like to understand how price per square metre varies across different
areas of London and how it has changed over time.

To do this we would like you to match two data sets. Using Land Registry
house price transaction data and Energy Performance Certificate data matching
by address to work out a price per square metre by postcode district (the
first part of a [UK
postcode](https://en.wikipedia.org/wiki/Postcodes_in_the_United_Kingdom) e.g.
`SE1` or `NW6`) over time.

Data
----
[Land Registry](https://en.wikipedia.org/wiki/HM_Land_Registry) residential
property transactions in London since 1995 at address level

[Energy Performance Certificate
(EPC)](https://en.wikipedia.org/wiki/Energy_Performance_Certificate_(United_Kingdom))
data for each local authority in London at address level

The EPC data is split into 33 different CSVs, contained within a zip file.
Only use the ‘certificates.csv’ file in each folder.  ‘recommendations.csv’ is
not required.

### Files

Please download the data from here:

https://drive.google.com/open?id=1wA7FspKM5bHYevSrM8f-IvksrRq1_JCp

File | Description
---- | -----------
`LondonLRData` | Land Registry transaction data
`LandRegistryColumnDefinitions.csv` | Land Registry column names
`LondonEPCs.zip` | Energy performance certificate data
`EPCColumnDefinitions.csv` | Energy performance certificate column names

Tasks
-----

Some of the tasks we think you’d carry out as part of this test (not in order):

- Merge the EPC data files
- Clean the data
- Create postcode district strings from postcodes
- Create logic to match two data sets on address fields
- Work out the price/floor area by year by postcode district


What we’d like to see:
----------------------

- Tests! please include any instructions and/or dependencies that we will need
  in order to run your tests.
- We work with git for version control, please include your .git folder when
  you compress this folder and send it back to us - You should feel free to
  commit at any point in the process.
- Instructions on how to set up and run the environment for your code to work

Background
----------

Not essential but if you want to know more about the data there is some
background here:

- [Land Registry data](http://landregistry.data.gov.uk/app/root/doc/ppd)
- [EPC data](https://epc.opendatacommunities.org/docs/guidance)

