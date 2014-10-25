This document describes the functioning of the run_analysis.R script and provides instructions to execute it.

Overview of run_analysis.R Script: This R script calculates the mean of selected measurements calculated based on the Samsung S II Sensor Data for different specified physical activities and the selected subjects who performed those activities. 

Instructions to run run_analysis.R script.

1. The Samsung Dataset should be downloaded from the link https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.
2. The downloaded file should be then unzipped which will extract a folder "UCI HAR Dataset".
3. The run_analysis.R script should be placed inside the folder "UCI HAR Dataset" kepping all the subfolders intact.
4. The run_analysis.R script should be then ready for execution.

Input Datasets to the run_analysis.R:

1. train/X_train.txt - This dataset contains the 
2. test/X_test.txt
3. train/y_train.txt
4. test/y_test.txt
5. activity_labels.txt

There are two datasets that contains different measurements calculated on Samsung SII Sensor data. One dataset has the training data and the other has the test data. There are two other datasets describing the activity carried out in each observation. There are another dataset that relates the activity label with the activity name.



Functions of run_analysis.R:
 

