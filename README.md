# Getting And Cleaning Data

# Course Project

Source data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

(1) Unzip the source data into a folder on your local drive such as /users/username/GettingAndCleaningData
(2) Put run_analysis.R into the same folder.
(3) Set the working director in RStudio setwd("/users/username/GettingAndCleaningData")
(4) Execute the script by running the following code: source("run_analysis.R")
(5) data_set_with_averages.txt file will be created in the working directory and will contain the output.

Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.
