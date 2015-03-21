## Getting and Cleaning Data 

# Course Project

This file describes how the script run_analysis.R works.

The data for the project was downloaded by the following link: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Script run_analysis.R performs the following:

- Merges the training and the test sets using rbind
- Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement
- Reads activity_labels.txt and uses descriptive activity names from file to name the activities in the data set
- Labels the data set with descriptive variable names and saves data to file merged_data.txt
- Creates independent tidy data set with the means value of each measurement for each activity and each subject and saves data to file data_set_with_means_values.txt
