
R script called run_analysis.R that does the following:
Merges the training and the test sets to create one data set by rbind function.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set.
Appropriately labels the data set with descriptive variable names. 
From the data set all_data, creates the averages_data: independent tidy data set with the average of each variable for each activity and each subject.

# Variables

`x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` - data from the files.
`x_data`, `y_data` and `subject_data` - merged datasets for analysis.
`features` - data from the file features.txt.
'mean_and_std_features' -  measurements on the mean and standard deviation for each measurement.
`activities` - activities data set.
'all_data' - contains `all_data` merges `x_data`, `y_data` and `subject_data'.
'averages_data' - independent tidy data set with the average of each variable for each activity and each subject.
