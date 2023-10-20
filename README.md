# CitiBikeNYC
Data Clean for CitiBike Analysis in Tableau

## Table of Contents

- [About](#about)
- [Usage](#usage)

## About

Tableau Public has a limitaion of 1 G data.To analyze data from the CitiBike program for New York City using Tableau it was first necessary to clean and reduce the amount of data needed without losing any valuble information. I did this by cleaning out any rows with empty fields, outliers, etc. Then I pulled the repetative data fields containing station details and created a reference table to find the detailed information for each station only when needed.

## Usage

The files used for this are too large for github. Even compressed the files were too large for the repository.

First you must download the following files from https://s3.amazonaws.com/tripdata/index.html


202307-citibike-tripdata.csv.zip

202304-citibike-tripdata.csv.zip

202301-citibike-tripdata.csv.zip

Save these in the Resources folder

Then run citibike.ipynb. This will write the 2 data files we want in the cleaned folder.

citibike_stations.csv

citibike_ly_clean.csv

Then I loaded these two files into Tableau to preform my anaylsis.