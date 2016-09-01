# Getting and Cleaning Data Course Project 
  https://www.coursera.org/learn/data-cleaning
  
  This project intends to demonstrate the importance and the ability to collect, work with and clean a data set. The goal is to prepare a tidy data that can be use for later analysis. 
  

 The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. 
 full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
 
 Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
 
## Project Summary

-Merges the training and the test sets to create one data set.

-Extracts only the measurements on the mean and standard deviation for each measurement.

-Uses descriptive activity names to name the activities in the data set

-Appropriately labels the data set with descriptive variable names.

-From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##What you find in this repository?

CodeBook.md: information about raw and tidy data set

README.md: this file

run_analysis.R: R script to transform raw data set in a tidy one

tidydata.txt : file with the tidy data set

##How to create the tidy data set ?

Source run_analisys.R script (it requires the plyr package): source('run_analysis.R')


