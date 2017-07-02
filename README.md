# Getting-and-Cleaning-Data-Course-Project

## Homework Assignment

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected. You should create one R script called run_analysis.R that does the following.

* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement.
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names.
* From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Script Steps

1) Check if the data is in your working directory. If not, download and unzip.
2) Download all the relevant files from the data set.
3) Start combining data (XTest with XTrain, YTest with YTrain, SubjectTest with SubjectTrain).
4) Set column names.
5) Filter for columns with means and standard deviations within the combined XTestTrain table.
6) Replace activities with descriptive names.
7) Finish combining the data set.
8) Clean column names.
9) Create a tidy data set based on subject and activity.
