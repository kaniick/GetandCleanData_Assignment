##Introduction
This repository is for the Coursera Data Science Specialization Track in Getting and Cleaning Data it contains R code that downloads and does some preprocessing on Human
Activity Recognition data set. The full description and the data can be found
[here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

####The script `run_analysis.R`
- The script assumes that `plyr` library is already installed.
- It then downloads the data from
  [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.html)
- merges the training and test sets to create one data set
- replaces `activity` values in the dataset with descriptive activity names
- extracts only the measurements (features) on the mean and standard deviation
  for each measurement
- appropriately labels the columns with descriptive names
- creates a second, independent tidy dataset with an average of each variable
  for each each activity and each subject. In other words, same type of
  measurements for a particular subject and activity are averaged into one value
  and the tidy data set contains these mean values only. The processed tidy data
  set is also exported as csv file.

##Other Information
From more information on this R Code please look at [`CodeBook.md`](https://github.com/kaniick/GetandCleanData_Assignment/blob/master/CodeBook.md) for details.


 
