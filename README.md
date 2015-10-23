# Getting-and-Cleaning-Data-Assignment
Peer Assessment for Course Project
1.	Merges the training and the test sets to create one data set
    Read and convert files into R files
    Merge files in folder Train and Test respectively
    Merge files from folder Train and Test
2.	Extracts only the measurements on the mean and standard deviation for each measurement
    Read the file features.txt
    Create the list of measurements
    Extract the data based on the list
3.	Uses descriptive activity names to name the activities in the data set
    Read the file activity_label.txt
    Name for the columns
    Use vertical lookup to name the activities in the data set
4.	Appropriately labels the data set with descriptive variable names.
    Create the list identical to step 2
    Create the column names based on the list
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject
    Calculate the average by using colMeans
    Convert the list into the data frame
    Modify 2 variables
    Rename the rows
