# Code Book 
This code book describes variables, data, and any transformations or work  performed to clean up the data. 
These efforts resulted into a clean and tidy dataset - please see [tidy_data.csv](https://github.com/zezutom/GetAndCleanDataProject/blob/master/tidy_data.csv).

## Data Source Details
* Original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
* Information provided by the authors: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## Dataset Description
Full details and explanations can be found in 'README.txt' in the ZIP file containing the original data source.

### Quick facts
* the experiments involved a group of 30 volunteers (19 - 48 years of age)
* each person performed six activities while wearing a smartphone (Samsung Galaxy S II) on their waist
* the activities consisted of three types of walking (flat, upstairs and downstairs), sitting, standing and laying
* the experiments have been [video recorded (YouTube)](http://www.youtube.com/watch?v=XOEN9W05_4A)

### Data Partitioning
The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

### Measurements
The following sensor signals was captured using the smartphone's embedded accelerometer and gyroscope:
* 3-axial linear acceleration
* 3-axial angular velocity at a constant rate of 50Hz

The captured signals were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). From each window, a vector of features was obtained by calculating variables from the time and frequency domain. The file 'features_info.txt' has more details.

## Feature Selection

## Transformations

## Other Information
