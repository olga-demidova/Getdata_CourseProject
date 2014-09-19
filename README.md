Getdata_CourseProject
=====================

Course Project for Coursera class "Getting and Cleaning Data"

This code performs the following steps:

1. Loads training dataset on UCI HAR from your working directory (7352 observations)
2. Loads test dataset on UCI HAR from your working directory (561 observations)
3. Merges training and test datasets in one large dataset (10299 observations)
4. Selects only the mean and the standard deviation of the measured signals.
5. Changed activity id (1-6) to activity label (LAYING, SITTING, STANDING, WALKING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS)
6. Reshapes data creating independent tidy data set with the average of each variable for each activity and each subject
