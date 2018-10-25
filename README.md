# Introduction

This is a data engineering test.  Take as long as you need or you think is reasonable. You don't need to complete all the requirements if you are pushed for time, however your solution should give us enough code to confirm that you are a skilled engineer.

You should use Python 3 and PostgreSQL, with whatever libraries or frameworks are appropriate.  Please note though we’ll need to be able to replicate and run your solution, so make sure to include information on how you set up the database, all your scripts and any migrations, imports etc.

Please do not make your solution publicly available, just compress this folder and send it back to us.

# Understanding Prices in London

We would like to understand how price per square metre varies across different areas of London and how it has changed over time.

To do this we would like you to match two data sets.  Using Land Registry house price transaction data and Energy Performance Certificate data matching by address to work out a price per square metre by postcode district (the first part of a postcode e.g. SE1 or NW6) over time.

To do this task please use Python and SQL in anyway you see fit.

# Data
Land Registry residential property transactions in London since 1995 at address level
Energy Performance Certificate (EPC) data for each local authority in London at address level

The EPC data is split into 33 different csvs, contained within a zip file.  Only use the ‘certificates.csv’ file in each folder.  ‘recommendations.csv’ is not required.

# Files
Please download the data from here:  https://drive.google.com/file/d/1w0WHZe_m8kmVXMUrgireMwHtE5yxee5T/view?usp=sharing

LondonLRData- Land Registry transaction data
LandRegistryColumnDefinitions.csv - Land Registry column names
LondonEPCs.zip - Energy performance certificate data
EPCColumnDefinitions.csv - Energy performance certificate column names

# Background
Not essential but if you want to know more about the data there is some background here.
- Land Registry data detail - http://landregistry.data.gov.uk/app/root/doc/ppd
- EPC data detail - https://epc.opendatacommunities.org/docs/guidance

And information on SQL Lite is here
- https://www.sqlite.org/index.html

Some of the tasks we think you’d carry out as part of this test (not in order):

- Merge the EPC data files
- Clean the data
- Create postcode district strings from postcodes
- Create logic to match two data sets on address fields
- Work out the price/floor area by year by postcode district


# What we’d like to see
- Tests! please include any instructions and/or dependencies that we will need in order to run your tests.
- We work with git for version control, please include your .git folder when you compress this folder and send it back to us - You should feel free to commit at any point in the process.
- Instructions on how to set up and run the environment for your code to work


# Feel free to ask any questions about the test, the data or your solution.


