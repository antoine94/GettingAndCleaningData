##Getting and Cleaning Data - Course Project

In this project for the Getting and Cleaning Data course, the R script, run_analysis.R, does the following:

Download the zip file if it is not already present in the working directory.
Unzip the downloaded file.
Load the activities and features tables.
Loads both the training and test datasets, from the X, Y and subject files.
Merges the datasets by rows.
Select only interesting variables from the resulting dataset (mean and std).
Merges the datasets by adding the subject and activity columns, to get only one big dataset.
Converts the activity and subject columns into factors and replace the activities identifiers to understandable labels.
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidyData.txt
