Introduction

The purpose of this project is to create one R script that demonstrates ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

A full description of data to be utilized for this project is available at the site:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

###Task at hand The script will perform following steps on the downloaded data

Merges the training and the test sets to create one data set
Extracts only the measurements on the mean and standard deviation for each measurement
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Steps to recreate this on your system

Download the data file mentioned above and unzip it in your working directory. Unzip should create a folder "UCI HAR Dataset"

Download run_analysis.R from the repository in your working directory, this file is located at the same level as this README.md

Read the CookBook.md or the comments in the script regarding details of the functioning of the script. The details of the data can be found under "UCI HAR Dataset\README.txt"

Run the following in your R

 `source("run_analysis.R")`
This should end up generating "Course3_Project_tidy.txt" file in your working directory. This file is the result of final step of creating a tidy data set with the average of each variable for each activity and each subject
