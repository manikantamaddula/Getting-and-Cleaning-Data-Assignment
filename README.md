# Getting-and-Cleaning-Data-Assignment
This project is done as a part of Getting and Cleaning Data Course in coursera.

The R script, run_analysis.R, does the following:

1. Download the dataset if it does not already exist in the working directory. And keep it in the working directory. Data can be downloaded from this link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
8. The end result is shown in the file tidy.txt.
