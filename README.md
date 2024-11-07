# Getting and Cleaning Data - Course Project

This project is part of the "Getting and Cleaning Data" course. It demonstrates the ability to collect, work with, and clean a data set from the accelerometers of Samsung Galaxy S smartphones.

## Project Overview
The goal of this project is to create a tidy dataset that can be used for further analysis. The raw data was collected from experiments involving human subjects performing various activities.

## Files
- `run_analysis.R`: This R script performs data cleaning and processing.
- `CodeBook.md`: This file describes the variables, data, and transformations applied to clean up the data.
- `FinalData.txt`: This is the output tidy data set.

## Instructions
1. Place the `run_analysis.R` script in your working directory.
2. Run the script. It will automatically download the dataset, clean the data, and save the tidy data set to `FinalData.txt`.

## Summary of the Script
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation.
3. Adds descriptive activity names.
4. Appropriately labels the data set with descriptive variable names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and subject.
