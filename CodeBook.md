Course Project Code Book
Original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The R script (run_analysis.R) performs the following to clean up the data:

(1) Merges the training and test sets to create one data set for each of the focus areas (X, Y & Subject).

(2) Reads features.txt and extracts the measurements of the mean and standard deviation for each one in decimal form.

(3) Reads activity_labels.txt and applies descriptive activity names to name the activities in the data set:
(a) walking (b) walkingupstairs (c) walkingdownstairs (d) sitting (e) standing (f) laying

(4) Appropriately labels the data set with descriptive variable names from step 3. 

(5) Using the data set from step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
