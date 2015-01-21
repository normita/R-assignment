# R-assignment

Assignment:

You should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Steps to work on this course project

Guide:

A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
Download the data for the project from the link below: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
Put the downloaded dataset folder (UCI HAR Dataset) in a convenient folder on your local disk.
Put run_analysis.R in the same folder as UCI HAR Dataset;
Using setwd() function in RStudio, set the folder where run_analysis.R and the dataset folder are as your working directory.
Run run_analysis.R using source("run_analysis.R");
It will install reshape2 and data.table automatically.
Finally, it will generate a new file tiny_data.txt in your working directory.
