Course Project - Getting and Cleaning Data
=========================

This is a repository for code written for the Getting and Cleaning Data Coursera course project through Johns Hopkins University.

## Course Project

* Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, here mine is "~/Desktop/Cousera/Getting and Cleaning Data/Course Project - Getting and Cleanning Data" without quotes.

* Put run_analysis.R into "~/Desktop/Cousera/Getting and Cleaning Data/Getting-and-Cleaning-Data---Course-Project"

* In RStudio: setwd("~/Desktop/Cousera/Getting and Cleaning Data/Getting-and-Cleaning-Data---Course-Project"), followed by: source("run_analysis.R")

* Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.(I copied this paragraph from rfoxfa who have learned this course before, he is in my following list)