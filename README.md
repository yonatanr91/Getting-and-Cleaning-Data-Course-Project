# Getting-and-Cleaning-Data-Course-Project

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

## Data Information

Information about the relevant data from this link: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

Citation Request:

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.

##Homework Assignment

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected. You should create one R script called run_analysis.R that does the following.

*Merges the training and the test sets to create one data set.
*Extracts only the measurements on the mean and standard deviation for each measurement.
*Uses descriptive activity names to name the activities in the data set
*Appropriately labels the data set with descriptive variable names.
*From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
