# Getting and Cleaning Data - Course Project

The R script, 'run_analysis.R', does the following:

1. Download the dataset if it does not already exist in the working directory.
   Data for this project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

2. Load the activity and feature info
3. Load both the traning and test datasets, keeping only those columns which
   reflect a mean or standard deviation
4. Load the activity and subject data for each dataset, and merges those
   columns with the dataset
5. Merge the two datasets
6. Convert the 'activity' and 'subject' columns into factors
7. Create a tidy dataset that consists of the average of each variable for each
   activity and subject pair.

The end result is show in the file 'tidy.txt'.

