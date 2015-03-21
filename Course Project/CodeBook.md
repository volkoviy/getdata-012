## Getting and Cleaning Data 

# Course Project Code Book

Script run_analysis.R uses the following variables:

- X - 10299x561 data list containing data merged from train/X_train.txt and test/X_test.txt 
- S - 10299x1 data list containing data merged from train/subject_train.txt and test/subject_test.txt
- Y - 10299x1 data list containing data merged from train/y_train.txt and test/y_test.txt
- features - 561x2 data list containing data from file features.txt
- indices_of_good_features - 66 data vector with indices of attributes with measurements on the mean and standard deviation
- activities - 6x2 data list containing data from file activity_labels.txt
- cleaned - 10299x68 data list containing data merged data with descriptive activity names (in the second column)
- uniqueSubjects - vector of subjects' unique values from S
- numSubjects - number of elements in vector uniqueSubjects
- numActivities - number of activities read from file activity_labels.txt
- numCols - number of columns in cleaned data list
- result - 180x68 data list containing tidy data set with the average of each variable for each activity and each subject