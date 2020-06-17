# Starbucks Capstone Project
Nanodegree capstone project

## Project Motivation
The motivation for this project is to solve the problem from start to finish in data science process. And finish Capstone project :)

## Installation
The code should run with no issues using Python versions 3.*.

Libraries:
* numpy
* pandas
* matplotlib
* seaborn
* sklearn

## Files

### Main file
Starbucks_Capstone_notebook.ipynb - containing the analysis for the project

### Data Sets
The data is contained in three files:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

##### portfolio.json

* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

##### profile.json

* age (int) - age of the customer
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

##### transcript.json

* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

## Result
The main conclusions on the problem can be found in the Results section at the post available [here](https://medium.com/@almas_aisin/optimizing-app-offers-with-starbucks-893c83900d06).

## Licensing
Data provided by Udashiti as part of Data Scientisi Nanodegree Program
