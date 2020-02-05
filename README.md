# Cleaning and Getting Data course project
Coursera Getting and Cleaning Data Course Final Project

An analysis of accelerometer data generated from an experiment with Samsung Galaxy S smartphones.

Dataset
Human Activity Recognition Using Smartphones


Contents
- CodeBook.md - a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data
- run_analysis.R - performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
	Merges the training and the test sets to create one data set.
	Extracts only the measurements on the mean and standard deviation for each measurement.
	Uses descriptive activity names to name the activities in the data set
	Appropriately labels the data set with descriptive variable names.
	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
- FinalData.txt is the exported final data after going through all the sequences described above.

Getting started
  1. Read through the CodeBook and the run_analysis.R script to get a general understanding of this project, the steps taken in the analysis, and the output file.
  2. Make sure the experiment data is downloaded and extracted to a folder in the project directory called UCI HAR Dataset.
  3. Run the run_analysis.R script.